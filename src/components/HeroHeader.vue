<template>
  <div class="hero-header">
    
    
    <div class="hero-content">
      <div class="left-content">
        <img src="../assets/img/logo.png" alt="" class="hero-logo">
        <div class="hero-title-container">
          <h1 class="hero-title">Qovery Engine</h1>
          <a href="#" class="github-btn"><img src="../assets/img/githubStarBtn.png" alt=""></a>
        </div>
        
        <div class="hero-left-content">
          <h2 class="hero-subtitle">Abstraction layer to deploy microservices applications on any Cloud provider.</h2>
          <p class="hero-text">Qovery Engine is an open-source abstraction layer product that turns easy apps deployment on AWS, GCP, Azure and others Cloud providers.</p>
          <div class="left-content-btn-container">
            <a href="#"><img src="../assets/img/githubBtn.png" alt="" class="see-on-github-btn"></a>
            <a href="#"><img src="../assets/img/discordBtn.png" alt="" class="discord-btn"></a>
          </div>
        </div>
      </div>

      <div class="right-content">
        <img src="../assets/img/hero-decoration.png" alt="" class="right-content-img">
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Hero-Header',
  props: {
    msg: String
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hero-header{
  background-color: #151B2B;
  height: auto;
}

.left-content{
  margin: 10px;
  text-align: left;
}

.hero-title-container{
  display: flex;
  flex-direction: row;
}

.hero-logo{
  margin-top: 20px;
}

.github-btn{
  height: 20px;
  margin: auto;
}

.hero-title,
.hero-subtitle{
  color: white;
}

.hero-text{
  color: #8686B2;
}

.left-content-btn-container{
  display: flex;
  flex-direction: row;
  margin: 50px auto;
  justify-content: space-around;
}

.right-content-img{
  width: 100%;
  margin-bottom: 25px;
}

@media screen and (min-width: 700px) {
    .hero-content{
      display: flex;
      flex-direction: row;
      padding: 0 50px;
      justify-content: center;
    }

    .hero-logo{
    
    }

    .left-content{
      width: 40%;
      margin-right: 100px;
    }

    .right-content{
      width: 40%;
      margin-top: 5%;
    }
}

@media screen and (min-width: 1025px) {
    .hero-content{
      display: flex;
      flex-direction: row;
      padding: 50px 50px;
      justify-content: center;
    }

    .hero-logo {
      margin-bottom: 100px;
    }

    .hero-title {
      margin-right: -175px;
    }

    .left-content{
      width: 35%;
      margin: 0 100px 0 0;
    }

    .left-content-btn-container {
      justify-content: left;
    }

    .see-on-github-btn {
      margin-right: 20px;
    }

    .right-content{
      width: 40%;
    }

    .right-content-img{
      margin-top: 60px;
    }
}

</style>
