---
permalink: /markdown/
title: "Components of my personal website"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Self-Introduction 

* Basic information about me
* What's unique about me personally
* My previous experience
* My interest and hobbies
* News

## Publications
* Currently here are the main elements of my undergraduate thesis
* In the future, there will be a record of my academic publications

## Resources
 * [Liquid syntax guide](https://shopify.github.io/liquid/tags/control-flow/)
 * [MathJax Documentation](https://docs.mathjax.org/en/latest/)

## MathJax 

Support for MathJax Version 3.0 is included in the template:

$$
\displaylines{
\nabla \cdot E= \frac{\rho}{\epsilon_0} \\\
\nabla \cdot B=0 \\\
\nabla \times E= -\partial_tB \\\
\nabla \times B  = \mu_0 \left(J + \varepsilon_0 \partial_t E \right)
}
$$

The default delimiters of `$$...$$` and `\\[...\\]` are supported for displayed mathematics, while `\\(...\\)` should be used for in-line mathematics (ex., \\(a^2 + b^2 = c^2\\))

**Note** that since Academic Pages uses Markdown which cases some interference with MathJax and LaTeX for escaping characters and new lines, although [some workarounds exist](https://math.codidact.com/posts/278763/278772#answer-278772).

## Markdown guide

Academic Pages uses [kramdown](https://kramdown.gettalong.org/index.html) for Markdown rendering, which has some differences from other Markdown implementations such as GitHub's. In addition to this guide, please see the [kramdown Syntax page](https://kramdown.gettalong.org/syntax.html) for full documentation.  

### Header three

#### Header four

##### Header five

###### Header six

## Blockquotes

Single line blockquote:

> Quotes are cool.



**Footnotes**

The footnotes in the page will be returned following this line, return to the section on <a href="#footnotes">Markdown Footnotes</a>.

