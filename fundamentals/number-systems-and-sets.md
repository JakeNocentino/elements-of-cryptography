# Basic Set Theory

Set theory is a topic of study in its own right. This section will only provide a brief overview of the parts of set theory that pertain to this tutorial—a _subset_ of set theory you could say.

### Definition

* A _set_ can be simply defined as: a collection of _elements_.
* An _element_ is any member of a set.

#### Example

If we have a set $$C$$, which is a collection of colors, we could denote $$C$$ as follows:

$$
C =\left \{ red,\:blue, \:green \right \}
$$

This means $$red$$, $$blue$$, and $$green$$ are elements of $$C$$. We can also show membership of a set like this: 

$$
blue \in C
$$

This reads "$$blue$$ is an element of $$C$$" or simply "$$blue$$ is in $$C$$". If we want to say something is _not_ an element of a set, we just slash the element symbol like so:

$$
yellow \notin C
$$

A set which contains an _ellipsis_ $$\ldots$$ means that the visible pattern of elements extends. For example, the set of positive even numbers $$E$$ might be denoted:

$$
E=\left \{2,\:4,\:6,\:\ldots \right \}
$$

#### Set Builder Notation

Set builder noation is a shorthand way to define a set. For example, if $$O$$ is the set of all odd numbers, we could write:

$$
O=\left \{ 2n+1\mid n\in \mathbb{Z} \right \}
$$

Looks cryptic, I know, but let's break it down. 

* The vertical bar $$\mid$$ means "such that".
* To the left of the vertical bar is the _formula_ for all elements in the set: $$ 2n+1$$.
* To the right of the vertical bar is the _constraint_ for all elements in the set: $$n\in \mathbb{Z}$$.
* $$\mathbb{Z}$$ is the set of all _integers_ \(explained in detail in **Sets Of Numbers** below\).

Putting it all together and reading it aloud, it says: "$$O$$ is the set of all $$2n + 1$$ such that $$n$$ is an integer". If we plug in any integer for $$n$$, we will get an odd number. And if we plug in all integers for $$n$$, we will get the set of all odd numbers.

{% hint style="info" %}
The vertical bar $$\mid$$ can also mean "divides" in some contexts. For example, $$x \mid y$$  can mean $$x$$ divides $$y$$. See the **Notation Refernece** for more info.  
{% endhint %}

### Sets of Numbers

Cryptography primarily makes use of the _integers_ $$\mathbb{Z}$$, but for perspective, here is a quick rundown of some common number sets.  

#### Natural Numbers

Denoted by $$\mathbb{N}$$, the set of natural numbers consists of the numbers we naturally use to count. In other words, the whole, positive numbers. Some mathematicians include zero while others don't.

$$
\mathbb{N} = \left \{ 0,\:1,\:2,\:3,\:... \right \}\quad or\quad \mathbb{N} = \left \{ 1,\:2,\:3,\:... \right \}
$$

#### Integers

Denoted by $$\mathbb{Z}$$, the set of integers includes all positve and negative whole numbers and zero.

$$
\mathbb{Z} = \left \{...\:,-3,\:-2,\:-1,\: 0,\:1,\:2,\:3,\:... \right \}
$$

#### Rational Numbers

Denoted by $$\mathbb{Q}$$ \(for quotient\), the set of rational numbers can be defined as:

$$
\left \{\frac{a}{b}\mid a,b\in\mathbb{Z},b\neq0\right \}
$$

#### Real Numbers

Denoted by $$\mathbb{R}$$, the set of real numbers includes all rational, irrational, and transcendental numbers. That is, it includes all previously mentioned sets as well as numbers such as $$\pi$$, $$e$$, and  $$\sqrt { 2 } $$.



