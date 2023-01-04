<script setup>
//import { RouterLink, RouterView } from 'vue-router'
//import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
    <div class="about-us">About Us</div>

    <h1 class="Itinerary_Pro">Itinerary Pro</h1>

    <div class="plane">✈️</div>

    <h1 class="Get_Started">Get Started</h1>

    <div class="post"><img src="./assets/Postcards.png" height="741"></div>
</template>



<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Alfa+Slab+One&display=swap');
@import url('https://fonts.googleapis.com/css2?family=DM+Sans&display=swap');
.about-us {
position: absolute;
width: 155px;
left: -326px;
top: -80px;

font-family: 'Alfa Slab One';
font-style: normal;
font-weight: 400;
font-size: 25px;
line-height: 27px;
text-align: center;

color: #FFFFFF;

text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25);
  }

  .Itinerary_Pro {
position: absolute;
width: 601px;
height: 64px;
left: 0px;
top: 220px;

font-family: 'Alfa Slab One';
font-style: normal;
font-weight: 400;
font-size: 81px;
line-height: 82px;
text-align: center;

color: #FFFFFF;

mix-blend-mode: normal;
text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25);
  }

  .plane {
position: absolute;
width: 30px;
height: 30px;
left: 360px;
top: 450px;

font-family: 'DM Sans';
font-style: normal;
font-weight: 700;
font-size: 30px;
line-height: 39px;

color: #FFFFFF;
  }

  .Get_Started {
    position: absolute;
width: 300px;
height: 36px;
left: 158px;
top: 450px;

font-family: 'DM Sans';
font-style: normal;
font-weight: 700;
font-size: 35px;
line-height: 39px;

color: #006E8F;

text-shadow: 0px 0px 3.5px #1B9FFF;
  }

  
    .post {
      left: 730px;
    transform: rotate(-90deg);
  }

</style>