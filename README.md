# APCalCheatSheet

I have 4 APs but...I'll update this anyway ;)

## AB

### Limits & Cont'd

#### BASIC:

**LEFT ≠ RIGHT >> lim x->c f(x) doesn't exist.**


When **x->infinity**, please **ignore small constants or terms with lower power.**


---

#### Evaluate Limits

- **Substitution**


If substitution doesn't work: **0/0**


- Try to **factorize** then cancel something causing 0/0.


If factorization doesn't work:

OR

**OTHER INDETERMINATE FORMS APPEAR after SUBSTITUTION**:

plz use **L.H** (*ONlY* FOR **INDETERMINATES** LIKE:  **0/0**,  **infinity/infinity**,  **infinity*0** ...etc.)


---


#### For prove 'f(x) is cont'd at x = c'

There are 3 STEPS must be met:


- f(c) exists (when answering questions, write f(c) = 'specific value')

- lim x->c f(x) exists (FIRST prove 'LEFT = RIGHT', if yes, lim x->c f(x) = 'specific value')

- lim x->c f(x) = f(c)


If any of the 3 steps is not met, there is a discontinuity.

**3 Type of Discontinuity**

- removable (you CAN cancel it)

- jump (you CANNOT cancel, and **LEFT ≠ RIGHT**)

- infinite(LEFT or RIGHT = infinity)


---


#### IVT

STEPS:

- Check if cont'd 

- if yes, calculate the value of the function at the **endpoints** of given x interval)

- Compare if the given value is between the 2 you calculated -> IVT works!

- Make your Conclusion



### Slope (Derivatives)

**Check if differentiable before answering**


Instant. Rate of Change = lim h->0 Avg. Rate of Change


#### MVT

When asking **'estimate IRC at x=c using values in the TABLE' :**


- Use MVT if differentiable (OF COURSE!)


  Choose two 'x' closest to 'c' (One Right and One Left), then just do what you usually do for ARC.
  

---

#### Monotonicity & Concavity & Extrema

If **f' > 0**, f **increases**.

*VICE VERSA*

If **f'' > 0**, f **concaves up** and f' **increases**.

And the **tangent line of f** will cause **Underestimation**, since it's **under the concave-up-curve**

*VICE VERSA*

If f' = 0 at x = c:

**Critical Point**

If f' **also changes its sign** here:

**'- to +' : Local/Relative Min**

**'+ to -' : Local/Relative Max**

If f'' = 0 at x = c (or f' changes its sign at x = c) AND f'' changes its sign:

**Inflection Point**

---

#### Tips for Calculating Derivatives 

DON'T:

- forget the 'USEFUL USUAL DERIVATIVES'

- forget about CHAIN RULE

- forget to check (redo) if you have remaining time

- SKIP STEPS (Especially for Emplicit)

---


### Integration

#### BASIC

**Area under the curve = Integral**

**FTC:**

f (x) = d/dx Integral f(t) dt from x to c(any constant)

**AVG value:**

1 / (b-a) * Integral f(x) dx from a to b

---

#### Riemann Sum


For functions **Increasing**: 


**LRS--UNDERestimation**


**RRS--OVERestimation**


*VICE VERSA*

---

Integration is **'antiderivative'**:

How you got 'Derivative' ?

**Reverse it, DON'T forget '+C'**

Then you get the **Integrals**

---

### Related Rates

- **Build a formula without derivatives, to express the relationship between quantities**

- Then, get the derivatives including given ones and those you need to calculate

- Plug the given values in, find the answer

---

### Slope Field

For a **Fraction** containing both x and y:

```csv
when x/y = 0, Slope is Horizontal or Veritical?, Conclusion
x, H, x/y
y, H, y/x
x, V, y/x
y, V, x/y
```
---

Generally, use such steps:

- '0' table above, to know if dy/dx is a fraction

- **Vertically** no change: dy/dx has **no 'x'**

- **Horizontally** no change: dy/dx has **no 'y'**

- Consider 'Neg/Pos' in each quadrant -> power of x and y

​---

### Area and Volume

**Same as Relative rates, you have to identify the relationship between quantities**

Then, construct an integration.

---

#### dy or dx?

dy or dx in the integration?

- check which axis you are going along:

- x-axis: use dx, y-axis: use dy(**turn x into the dependent variable**, eg: y=kx -> x = y/k)

---

### Differential Equations

DON'T WORRY if you have problems solving them:

You will get points for steps:

- 'Separation of variables': put y and dy together, x and dx together

- 'Make an integration'

- Write the integral with + C

- Put the 'Initial Condition' in

- Get the answer

---

## BC



### Improper Integrals


If upper and lower bounds contains where the function diverges, DIV.

---

### Parametric

Vectors: **Direction and Magnitude** (x, y and direction of the arrow)

Scalars: **MAGNITUDE ONLY** (length of the arrow: root(x^2+y^2) )

---

Tips for **2nd derivatives:**

**TREAT 'dy/dx' the same way as 'y'**

---

### Polar

TIPS:

Before Integrating Polar, softly sketch (all the way following the given graph) from 'theta = 0' , then you will get use to it (where it begins and ends) and NEVER mis-calculate the repeating part.

---

### Sequence and Taylor 

#### Sequence

- First, use '**limit of nth term**'. 

- If 0, continue. **If not 0, DIV**

- Use 'p' or 'geo' or  'alternating' acc. to the characteristic.

- IF can't, we still have: **limit/direct comparision, ratio**.

- IF they all die, USE **INTEGRAL TEST** as your ultimate weapon :) Enjoy!

Dont forget to test if **Conditionally or Absolutely**!

---

#### Taylor

Here, I only have one thing to say, b/c if you memorize how to expand a Taylor, you almost win the game.

**Dont forget to test the Convergence Interval (a,b) or [a,b] or (a,b] or [a,b), using the endpoints you calculated!**


---

```

To Be Cont'd

```
