---
layout: post
title: "Proyecto Euler - 1"
desc: "Suma de los múltiplos menores que un número dado"
keywords: "uno,dos"
date: 2016-09-26
categories: [math]
tags: [blog]
icon: icon-python
---

**Problema**

*Si listamos los números menores que 10 que son múltiplos de 3 o 5, obtenemos 3, 5, 6 y 9. La suma de estos múltiplos es 23.*

*Hallar la suma de los múltiplos de 3 o 5 menores que 100.*

Resolver:
\$\$
  \sum_{n\in M_k^N}n
$$

con
$$M_k^N:=\{ik:ik<N,i\in\mathbf N\}$$

sea (tiene max por contradiccion)
$$\alpha=\max\{i\in\mathbf N:ik<N\}$$

entonces
$$\alpha k<N$$

de donde
$$\alpha k\le N-1$$

y
$$N\le(\alpha-1)k$$

como
$$N\le(\alpha-1)k$$
