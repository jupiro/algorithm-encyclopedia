---
layout: entry
author: kimiyuki
reviewers:
date: 2020-07-09T00:00:00+09:00
updated_at:
tags: algorithm yen-algorithm
algorithm:
  input: 有向あるいは無向グラフ $G$ とその頂点 $s, t$ および自然数 $K$
  output: $G$ の $s-t$ 単純路であって $K$ 番目に短いもの
  time_complexity: $O(K V (E + V) \log V)$
  space_complexity:
  aliases:
description: Yen's algorithm とは、与えられたグラフ $G$ の $s-t$ 単純路であって $K$ 番目に短いものを $O(K V (E + V) \log V)$ で求めるアルゴリズムである。
draft: true
---

# Yen's algorithm