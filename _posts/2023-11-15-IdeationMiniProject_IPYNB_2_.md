---
layout: post
title: Ideation for Mini Project
description: The plan for our Computer Science A mini project.
categories: []
type: hacks
courses: {'csa': {'week': 13}}
---

## Project Idea
Our goal is to create an olympics for sorting algorithms and fibionachi sequences. We want to represent each sorting algorithm as a different athlete in the olympics: bubble, insertion, selection, and merge. And have each of the athletes compete agianst each other in different events representing different types of data sets to show how different sorting algorithms are better for different types of data: long, short, fully random, partially organized, etc.

## Event Examples
For long datasets we plan to create a cross country event where they have to circle a track twice similar to a 800m to show which sorting algorithm performs better for larger amounts of data.

## Track


```python
<img src=\"https://github.com/realethantran/fastpages_EthanT/assets/109186517/e2750a41-4e29-4f1c-b576-3a7d5db824b8\" width=\"100%\">
```

## Athlete Selection


```python
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    .athlete-selector {
      display: flex;
      justify-content: space-around;
      margin-top: 50px;
    }

    .athlete-option {
      position: relative;
      cursor: pointer;
      transition: transform 0.3s ease-in-out;
    }

    .athlete-option:hover {
      transform: scale(1.1);
    }

    .athlete-option img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
    }

    .selected-athlete {
      content: url("https://github.com/Code-Demons/miniproject/assets/40652645/213c0a9e-9c56-4484-9d69-3d1cc5984a5a");
    }

    .athlete-option:hover .selected-athlete {
      content: url("https://github.com/Code-Demons/miniproject/assets/40652645/6c68be6f-ae9d-44d6-8fb0-706604508827");
    }
  </style>
</head>
<body>

  <div class="athlete-selector">
    <div class="athlete-option">
      <img src="https://github.com/Code-Demons/miniproject/assets/40652645/4049e8b1-4b24-4c6f-a080-24504607145d" alt="Bubble Athlete">
      <div class="selected-athlete"></div>
    </div>
    <div class="athlete-option">
      <img src="https://github.com/Code-Demons/miniproject/assets/40652645/a4a76b53-cf84-4a7f-9093-bfa7dc6385c9" alt="Merge Athlete">
      <div class="selected-athlete"></div>
    </div>
  </div>

</body>
</html>

```

https://github.com/Code-Demons/miniproject/assets/40652645/4049e8b1-4b24-4c6f-a080-24504607145d
https://github.com/Code-Demons/miniproject/assets/40652645/213c0a9e-9c56-4484-9d69-3d1cc5984a5a
https://github.com/Code-Demons/miniproject/assets/40652645/a4a76b53-cf84-4a7f-9093-bfa7dc6385c9
https://github.com/Code-Demons/miniproject/assets/40652645/6c68be6f-ae9d-44d6-8fb0-706604508827

