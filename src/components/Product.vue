<script setup>
  import articles from './articles.vue';
</script>

<template>
  <articles>
    
  </articles>


  <div class="card-container">
    <div class="card">
      <img src="..src/assets/images/img_1.jpeg">
      <div class="card-content">
        <h3>Learn to live a healthy life with fitness</h3>
        <p>Changing your lifestyle with a fast paced life may seem hard or impossible, but with small steps each week you can achieve your dream physique and live a healthier life.</p>
        <a href="" class="btn">Read More</a>
      </div>
    </div>
    <div class="card">
      <img src="..src/assets/images/img_2.png">
      <div class="card-content">
        <h3>Understand how to do excercises properly</h3>
        <p>Just going to the gym and lifting weights won't make you healthy, after all it may even cause some harm to your body. We teach proper exercise techniques</p>
        <a href="" class="btn">Read More</a>
      </div>
    </div>
    <div class="card">
      <img src="..src/assets/images/img_3.png">
      <div class="card-content">
        <h3>Track your progress weekly</h3>
        <p>We're tracking your goal weight with body fat measures, weight and general feeling. You may have the same body weight but feel 10x better.</p>
        <a href="" class="btn">Read More</a>
      </div>
    </div>
  </div>

</template>

<style scoped>
  
  body {
    background-color: #f0f0f0;
    box-sizing: border-box;
   
  }

  .card-container {
    display:inline-block;
    margin-top: 100px;
    font-family: Montserrat;
  }

  .card {
    width: 325px;
    background-color: #f0f0f0;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0px 2px 4px rgba(0,0,0,0.2);
    margin: 20px;
    color: #000000;
  }

  .card-img {
    width:100%;
    height: auto;
  }

  .card-content {
    padding:30px;  
  }

  .card-content h3 {
    font-size: 28px;
    margin-bottom: 8px;  
  }

  .card-content p {
    color: #666;
    font-size: 15px;
    line-height: 1.3;
  }

  .card-content a {
    padding-top: 10px;
  }

  .card-content .btn {
    display: inline-block;
    padding: 8px 0px;
  }


</style>
