---
layout: post
title:  "Markdown Snippets"
date:   2023-08-29 20:36:45 -0700
categories: jekyll update
---
## How to name a file?

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

## How to write code?

{% highlight c++ %}
std::cout << "Hello World" << std::endl;
{% endhighlight %}

## How to link stuff?
`[jekyll`]`[jekyll-organization`] \
`[jekyll`]`(https://github.com/jekyll/jekyll`)

## How to write LaTex equations?
Inline $$\pi$$ this is the best.

Block Math Equations:
$$
 a + b + c
$$

$$
\begin{gather}
 \begin{bmatrix} \Phi_{11} & \Phi_{12} \\ \Phi_{21} & \Phi_{22} \end{bmatrix}
 =
 \frac{1}{\det(X)}
  \begin{bmatrix}
   X_{22} Y_{11} - X_{12} Y_{21} &
   X_{22} Y_{12} - X_{12} Y_{22} \\
   X_{11} Y_{21} - X_{21} Y_{11} &
   X_{11} Y_{22} - X_{21} Y_{12}
   \end{bmatrix}
\end{gather}
$$