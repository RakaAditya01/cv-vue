<template>

  <div class="about">
    <h3>Saya seorang Front End Developer dengan
pengetahuan menyeluruh tentang desain dan website. <br>
Saya mampu bekerja di bawah tekanan, dan juga
dapat bekerja secara individual maupun dalam tim. <br>
Saya mampu berkomunikasi dengan baik dengan rekan
tim, dan dapat mengatur waktu.</h3>
<br>
<h1>
  My Skill
</h1>
<div class="box">
  <ul>
    <li>
    <div class="lang"></div>
  <p>HTML5</p>
    <div class="bar-html">
      
       <div class="progress"></div>
       <div class="bar-percent">
        <span class="percent">80%</span>
       </div>
    </div>
    </li>
  </ul>

  <ul>
    <li>
    <div class="lang"></div>
  <p>CSS</p>
    <div class="bar-html">
      
       <div class="progress"></div>
       <div class="bar-percent-css">
        <span class="percent-css">90%</span>
       </div>
    </div>
    </li>
  </ul>

  <ul>
    <li>
    <div class="lang"></div>
  <p>JAVASCRIPT</p>
    <div class="bar-html">
      
       <div class="progress"></div>
       <div class="bar-percent-java">
        <span class="percent-java">50%</span>
        </div>
    </div>
    </li>
  </ul>
  <ul>
    <li>
    <div class="lang"></div>
  <p>VUE</p>
    <div class="bar-html">
      
       <div class="progress"></div>
       <div class="bar-percent-vue">
        <span class="percent-vue">50%</span>
        </div>
    </div>
    </li>
  </ul>
</div>
</div>
  
</template>

<script>
 
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
   
    /* display: flex; */
    align-items: center;
  }
  
}

.box{
  align-items: center;
  width: 800px;
  padding: 40px;
  background: #f3f3f3;
  box-shadow: 3px 3px 10px 3px rgba(0, 0, 0, 0.1);
}

ul li{
  list-style-type: none;
  padding: 10px;
}

/* HTML */
/* .lang{
  margin: 5px;
  font-size: 20px;
} */

.bar-html{
  width: 100%;
  background: #dfdfdf;
  overflow: hidden;
  padding: 5px;
}

.progress{
  float: left;
  padding: 5px;
}

.percent{
  color: white;
}

.bar-percent{
  width: 80%;
  background-color: red;
}
/* END */
/* CSS */
.percent-css{
  color: white;
}

.bar-percent-css{
  width: 90%;
  background-color: blue;
}
/* END */

/* JAVASCRIPT */
.percent-java{
  color: white;
  /* float: right; */
}

.bar-percent-java{
  width: 50%;
  background-color: blue;
}
/* END */

/* VUE */
.percent-vue{
  color: white;
  /* float: right; */
}

.bar-percent-vue{
  width: 50%;
  background-color: purple;
}
/* END */
</style>

