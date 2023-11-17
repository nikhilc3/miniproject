---
layout: default
title: Selection Example
permalink: /selectionplanning
---
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
