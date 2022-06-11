---
layout: post
title: データベース特別講義
tags: learning
category: memo
---
### データベースの勉強(Chapter1)
## 1. 用語
* superkey
    * Tupple を特定するキーの組み合わせ
* candidate key
    * superkey のうち一番小さい組み合わせ
    * candidate key が複数ある場合は primary key を指定する
* Relation are Unordered
* Relation Query Languages
    * Procedural versus non-procedural
* Relational Algebra 関数代数
    * 離散数学：値と演算子を考える
    * Select Operation
* Select Operation
    * σ Select: predicates 自体を and , or, not でつなぐことができる
    * ^ v not
* Project Operation
    * instructor
    * Composition of Relational Operations
* Cartesian-Product Operation
    * 掛け算： 集合の要素自体
    * 今後の味噌になる

* Join Operation
    * σ　instructor.id=teaches.id (instructor x teaches)
    * Join のオペレータを交えて書くことができる
* Set-Intersection Operation
* Set Difference Operation
    * 減算：
* Assignment Operation(変数に入れる)
* The Rename Operation
    * identical: 一字一句同じ
    * equivalent: 同値（結果的には同じ）
