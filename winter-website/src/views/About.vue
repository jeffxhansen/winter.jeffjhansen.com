<template>
  <div class="about">
    <h1 id="first">YOU LOST THE GAME :D</h1>
    <h1 id="second">YOU LOST THE GAME :D</h1>
    <h1 id="third">YOU LOST THE GAME :D</h1>
    <h1 id="fourth">YOU LOST THE GAME :D</h1>
    <h1 id="fifth">YOU LOST THE GAME :D</h1>
    <h1 id="sixth">YOU LOST THE GAME :D</h1>
  </div>
</template>

<style scoped>

.about {
  margin-top: 100px;
  display: flex;
  flex-direction: column;
}

#first {
  color: red;
  position: relative;
  animation-name: example1;
  animation-duration: 4s;
  animation-iteration-count: infinite;
}

@keyframes example1 {
  0%   {color:blue; left:0px; top:0px;}
  16%  {color:green; left:0px; top:10px;}
  32%  {color:yellow; left:0px; top:20px;}
  48%  {color:orange; left:0px; top:30px;}
  70%  {color:red; left:0px; top:20px;}
  86%  {color:purple; left:0px; top:10px;}
  100%  {color:blue; left:0px; top:0px;}
}

#second {
  margin-top: -56px;
  color: red;
  position: relative;
  animation-name: example2;
  animation-duration: 4s;
  animation-iteration-count: infinite;
}

@keyframes example2 {
  0%   {color:purple; left:0px; top:0px;}
  16%  {color:blue; left:0px; top:10px;}
  32%  {color:green; left:0px; top:20px;}
  48%  {color:yellow; left:0px; top:30px;}
  70%  {color:orange; left:0px; top:20px;}
  86%  {color:red; left:0px; top:10px;}
  100%  {color:purple; left:0px; top:0x;}
}

#third {
  margin-top: -56px;
  color: red;
  position: relative;
  animation-name: example3;
  animation-duration: 4s;
  animation-iteration-count: infinite;
}

@keyframes example3 {
  0%   {color:red; left:0px; top:0px;}
  16%  {color:purple; left:0px; top:10px;}
  32%  {color:blue; left:0px; top:20px;}
  48%  {color:green; left:0px; top:30px;}
  70%  {color:yellow; left:0px; top:20px;}
  86%  {color:orange; left:0px; top:10px;}
  100%  {color:red; left:0px; top:0px;}
}

#fourth {
  margin-top: -56px;
  color: red;
  position: relative;
  animation-name: example4;
  animation-duration: 4s;
  animation-iteration-count: infinite;
}

@keyframes example4 {
  0%   {color:orange; left:0px; top:0px;}
  16%  {color:red; left:0px; top:10px;}
  32%  {color:purple; left:0px; top:20px;}
  48%  {color:blue; left:0px; top:30px;}
  70%  {color:green; left:0px; top:20px;}
  86%  {color:yellow; left:0px; top:10px;}
  100%  {color:orange; left:0px; top:0px;}
}

#fifth {
  margin-top: -56px;
  color: red;
  position: relative;
  animation-name: example5;
  animation-duration: 4s;
  animation-iteration-count: infinite;
}

@keyframes example5 {
  0%   {color:yellow; left:0px; top:0px;}
  16%  {color:orange; left:0px; top:10px;}
  32%  {color:red; left:0px; top:20px;}
  48%  {color:purple; left:0px; top:30px;}
  70%  {color:blue; left:0px; top:20px;}
  86%  {color:green; left:0px; top:10px;}
  100%  {color:yellow; left:0px; top:0px;}
}

#sixth {
  margin-top: -56px;
  color: red;
  position: relative;
  animation-name: example6;
  animation-duration: 4s;
  animation-iteration-count: infinite;
}

@keyframes example6 {
  0%   {color:green; left:0px; top:0px;}
  16%  {color:yellow; left:0px; top:10px;}
  32%  {color:orange; left:0px; top:20px;}
  48%  {color:red; left:0px; top:30px;}
  70%  {color:purple; left:0px; top:20px;}
  86%  {color:blue; left:0px; top:10px;}
  100%  {color:green; left:0px; top:0px;}
}

.about h1 {
  width: 100%;
  height: 100%;
  text-align: center;
}
</style>
