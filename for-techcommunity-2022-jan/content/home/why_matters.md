---
weight: 30
markup: "html"
---
{{< slide bg-color="electric" >}}

## Why it matters to us?

------

- Working with other's code
- Working with legacy code
- New team member onboarding
- Knowledge transfer

------

### Code reading is hard

{{< div "fragment" >}}
{{< img src="/images/Code_Readings_book_cover.jpeg" height="600" >}}
{{< /div >}}

- We are not good at it <!-- .element: class="fragment" -->
- But spent more time on code reading than writing <!-- .element: class="fragment" -->

------

### An exercise

------

#### APL code
{{< code lang="APL" line-numbers="false" >}}
2 2 2 2 2 ⊤ n
{{< /code >}}

------

#### Java code
{{< code lang="Java" line-numbers="false" >}}
public class BinaryCalculator { 
   public static void mian(Integer n) {
      System.out.println(Integer.toBinaryString(n)); 
   }
}
{{< /code >}}

------

#### BASIC code
{{< code lang="BASIC" line-numbers="false" >}}
LET N2 =  ABS (INT (N))
LET B$ = ""
FOR N1 = N2 TO 0 STEP 0
     LET N2 =  INT (N1 / 2)
     LET B$ =  STR$ (N1 - N2 * 2) + B$
     LET N1 = N2
NEXT N1
PRINT B$
RETURN
{{< /code >}}

------

### Cognition Context

{{< img src="/images/Cognition_Context.png" height="700" >}}

------

### Cognitive Load

------

#### Intrinsic Load

{{< img src="/images/Intrinsic_load.png" height="500" >}}

How complex the problem is in itself

------

#### Extraneous Load

{{< img src="/images/Extraneous_load.png" height="500" >}}

What outside distractions add to the problem

------

#### Germane Load

{{< img src="/images/Germane_load.png" height="500" >}}

Brain's processing overhead

