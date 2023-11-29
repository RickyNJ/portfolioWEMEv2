<script>
  import weme1 from "D:/Code/portfolioWEME/src/resources/pictures/weme1.jpg";
  import weme2 from "D:/Code/portfolioWEME/src/resources/pictures/weme3.jpg";
  import weme3 from "D:/Code/portfolioWEME/src/resources/pictures/weme4.jpg";
  import weme4 from "D:/Code/portfolioWEME/src/resources/pictures/weme6.jpg";
  import weme5 from "D:/Code/portfolioWEME/src/resources/pictures/weme7.jpg";

  import { onMount } from "svelte";
</script>

<body>
  <div id="showcaseWrapper" class="container">
    <div id="showcaseImage1" class="imagediv">
      <img src = {weme1} class='image' alt="persoon1">
    </div>
    <div id="showcaseImage2" class="imagediv">
      <img src = {weme2} class='image' alt="persoon1">
    </div>
    <div id="showcaseImage3" class="imagediv">
      <img src = {weme3} class='image' alt="persoon1">
    </div>
    <div id="showcaseImage4" class="imagediv">
      <img src = {weme4} class='image' alt="persoon1">
    </div>
    <div id="showcaseImage5" class="imagediv">
      <img src = {weme5} class='image' alt="persoon1">
    </div>
  </div>
</body>

<style>
  body {
    margin: 0px;
    overflow: hidden;
    min-height: 100vh;
    display: grid;
    align-items: center;
    justify-content: center;
    background: black; 
  }
  .container {
    width: 100%;
    display: flex;
    align-content: center;
    justify-content: center;
  }
  .imagediv {
    flex: 0 0 120px;
    transition: 0.5 ease;
    cursor: pointer;
    display: inline-block;
  }
  .image {
    aspect-ratio: 3/4;
    width: 50vh;
    border-radius: 5%;
    -webkit-filter: brightness(70%);
  }
  img:hover {
    animation-delay: 150ms;
    transform: scale(1.05);
    -webkit-filter: brightness(100%);
    transition: all 1s ease;
  }
  img:not(:hover) {
    animation-delay: 150ms;
    transition: transform 1s ease;
    transform: scale(1);
  }
</style>
