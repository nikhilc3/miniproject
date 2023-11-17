---
layout: default
title: Selection Example
permalink: /selectionplanning
---
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
      display: flex;
      flex-direction: column;
      align-items: center;
      position: relative;
      cursor: pointer;
      transition: transform 0.3s ease-in-out;
    }
    .athlete-option:hover {
      transform: scale(1.2);
    }
    .athlete-option img {
      width: 150px;
      height: 225px;
      border-radius: 50%;
    }
    .athlete-option span {
      margin-top: 10px;
      font-weight: bold;
    }
    /* Specific image for Bubble Athlete */
    .athlete-option.bubble:hover img {
      content: url("https://github.com/Code-Demons/miniproject/assets/40652645/213c0a9e-9c56-4484-9d69-3d1cc5984a5a");
    }
    /* Specific image for Merge Athlete */
    .athlete-option.merge:hover img {
      content: url("https://github.com/Code-Demons/miniproject/assets/40652645/adb81563-7fda-47ac-981a-620550ef59e9");
    }
    #attribute-section {
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
      background-color: #f0f0f0;
      padding: 20px;
      display: none;
    }
  </style>
</head>
<body>

  <div class="athlete-selector">
    <div class="athlete-option bubble" onmouseover="showAttributes('Billy Bubble Attributes')" onmouseout="hideAttributes()">
      <img src="https://github.com/Code-Demons/miniproject/assets/40652645/4049e8b1-4b24-4c6f-a080-24504607145d" alt="Bubble Athlete">
      <span>Billy Bubble</span>
    </div>
    <div class="athlete-option merge" onmouseover="showAttributes('Martin Merge Attributes')" onmouseout="hideAttributes()">
      <img src="https://github.com/Code-Demons/miniproject/assets/40652645/245c81fd-0ccd-4a52-acee-af09a34baaad" alt="Merge Athlete">
      <span>Martin Merge</span>
    </div>
  </div>
  
  <div id="attribute-section"></div>

  <script>
    function showAttributes(attributes) {
      document.getElementById("attribute-section").innerHTML = attributes;
      document.getElementById("attribute-section").style.display = "block";
    }

    function hideAttributes() {
      document.getElementById("attribute-section").style.display = "none";
    }
  </script>

</body>
</html>