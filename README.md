## Use Docker

```Bash
function sac() { \
  docker run --rm \
    -e SAC_DECK_CODE_HUGO_ARGS="--bind 0.0.0.0" \
    -e SAC_DECK_HTML_HUGO_ARGS="--gc --minify -b lftpb" \
    -v $(pwd):/home/linuxbrew/sac \
    -v $HOME/.sac/themes:/usr/local/share/sac/themes \
    -p 1313:1313 \
    -w /home/linuxbrew/sac \
    -it sacproj/sac:2.1.0 sac "$@"; }

function decktape() { \
  docker run --rm -t --net=host -v `pwd`:/slides \
  astefanutti/decktape "$@"; }
```

```
decktape --slides 1-7,17-27 http://localhost:1313 slides.pdf
```
