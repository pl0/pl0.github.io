Title:   this is meta data at top  
Author: plindsay
Email:  pl0@me.com
Date:   22 January 2018, 11:14:13 am


#hi  

    27 October 2015, 11:24:21 a.m.

| Header One | Header Two | Header Three | Header Four |
| ---------- | :--------- | :----------: | ----------: |
| Default    | Left       | Centre       | Right       |
| hi Peter| maybe| will work| 34 |

---

* Copy the HTML output directly to your clipboard -- so you can conveniently paste it into your favourite HTML editor[^fn-export];
* Export to a file.

[^fn-export]: When copying to clipboard, **Byword** will only place the equivalent of the `body` tag contents. On the other hand, when exporting to a file, a complete HTML file will be generated.



---

     not sure what this is but we will see

````
     
# Fibonacci numbers module

def fib(n):    # write Fibonacci series up to n
    a, b = 0, 1
    while b < n:
        print (b),
        a, b = b, a+b

def fib2(n): # return Fibonacci series up to n
    result = []
    a, b = 0, 1
    while b < n:
        result.append(b)
        a, b = b, a+b
    return result

fib(111116)
#fib2(11)

````
           
---     
     
and the `back tick` does this

an image here

![silly]("https://www.dropbox.com/s/incefwzo98ojtjd/car.png?dl=0" "what title")

* a list
* maybe

a link to [ bbc ](http://www.bbc.co.uk)

can also be done like this [bbc] and repeated [bbc] easily by putting link details at bottom of page.

Clicking this number[^fn-2] will lead you to a footnote.

[^fn-2]: Handy! Now click the return link to go back.


---

\\[ e^{i\pi }+1=0 \\] 

\\[ {x}_{1,2}=\frac{-b\pm \sqrt{b^2-4ac}}{2a} \\]

\\[ \int \sin x ~dx \\]
\\[ \Delta =\sum_{i=1}^N w_i (x_i - \bar{x})^2 \\]
\\[ I =  \int_{-\infty}^\infty f(x)\,dx   \\]
\\[ \begin{pmatrix}
e^{\beta (J + B)}  & e^{-\beta J}  \\
e^{-\beta J}  & e^{\beta (J - B)} 
\end{pmatrix} \\]

#### The Lorenz Equations

\\[\begin{aligned}
\dot{x} & = \sigma(y-x) \\\
\dot{y} & = \rho x - y - xz \\\
\dot{z} & = -\beta z + xy
\end{aligned} \\]


---

---

#### Maxwell’s Equations

\\[  \begin{aligned}
\nabla \times \vec{\mathbf{B}} -\, \frac1c\, \frac{\partial\vec{\mathbf{E}}}{\partial t} & = \frac{4\pi}{c}\vec{\mathbf{j}} \\   \nabla \cdot \vec{\mathbf{E}} & = 4 \pi \rho \\
\nabla \times \vec{\mathbf{E}}\, +\, \frac1c\, \frac{\partial\vec{\mathbf{B}}}{\partial t} & = \vec{\mathbf{0}} \\
\nabla \cdot \vec{\mathbf{B}} & = 0 \end{aligned}
\\]

---

#### A Rogers-Ramanujan Identity

\\[  1 +  \frac{q^2}{(1-q)}+\frac{q^6}{(1-q)(1-q^2)}+\cdots =
\prod_{j=0}^{\infty}\frac{1}{(1-q^{5j+2})(1-q^{5j+3})},
\quad\quad \text{for $|q|<1$}. \\]


---

#### The probability of getting \\(k\\) heads when flipping \\(n\\) coins is

\\[P(E) = {n \choose k} p^k (1-p)^{ n-k} \\]

---
---

#### The Cauchy-Schwarz Inequality

\\[ \left( \sum\_{k=1}^n a_k b_k \right)^2 \leq \left( \sum\_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right) \\]

---

#### A Cross Product Formula

\\[\mathbf{V}\_1 \times \mathbf{V}\_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0
\end{vmatrix} \\]

---




ok, try this now

> what do you think is it a quote or something ?

> not sure about this   
> ok yes this works

>> how about this ?

---

[this ](1.html) should be a link to the 1.html paged

---


*this* should be italics

**this** should be bold

---

In order to create valid [HTML], you need properly
coded syntax that can be cumbersome for 
"non-programmers" to write.


[HTML]: http://en.wikipedia.org/wiki/HTML
[BBC]: http://www.bbc.co.uk