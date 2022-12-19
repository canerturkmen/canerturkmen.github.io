---
title: "fun with cryptography"
date: 2023-04-26T00:00:00+01:00
math: true
draft: true
---

Just to kill time, I started following Dan Boneh's Coursera course on introductory cryptography (working backwards from a desire to understand what zkSNARKs are all about).
I'm only halfway through the course, and I already regret not having taken cryptography before. 
Here are some fun facts.

- Let $X \sim \mathcal{U}[\mathbb{B}^n]$, i.e., a uniformly distributed random variable over bitstrings of length $n$. Also, let $Y$ be another random variable distributed (according to some other arbitrary distribution) over $\mathbb{B}^n$. $X \oplus Y$ is uniformly distributed over $\mathbb{B}^n$, where $\oplus$ denotes the XOR operator. This is such a simple fact, and so obvious in hindsight. Yet, seeing it in the first chapter of a crypto course, given the context, one understands how profound it was all along.