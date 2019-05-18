---
layout: exercise
title: Exercise 1.1
permalink: /intro-exercises/ex_1/
breadcrumb: 1-Introduction
---

{% include mathjax_support %}


<div class="card">
    <div class="card-header p-2">
        <a href='ex_1/' class="p-2">Exercise 1</a>
        <button type="button" class="btn btn-dark float-right" title="Solve this Exercise" onclick="solve('ex1.1');" href="#"><i id="ex1.1" class="fas fa-pen" style="color:white"></i></button>
        <button type="button" class="btn btn-dark float-right" title="Edit this Question"  style="margin-left:10px; margin-right:10px;" onclick="upvote('ex1.1');" href="#"><i id="ex1.1" class="far fa-edit" style="color:white"></i></button>
    </div>
    <div class="card-body">
        <p class="card-text">{% include_relative question.md %}</p>
    </div>
</div>

<br>
