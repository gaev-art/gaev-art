<div class="frame">
  <div class="sky">
    <div class="star star1"></div>
    <div class="star star2"></div>
    <div class="star star3"></div>
    <div class="star star4"></div>
    <div class="star star5"></div>
    <div class="star star6"></div>
    <div class="star star7"></div>
    <div class="star star8"></div>
    <div class="star star9"></div>
    <div class="star star10"></div>
    <div class="star star11"></div>
    <div class="star star12"></div>
    <div class="star star13"></div>
    <div class="star star14"></div>
    <div class="star star15"></div>
    <div class="star star16"></div>
    <div class="star star17"></div>
    <div class="star star18"></div>
    <div class="star star19"></div>
    <div class="star star20"></div>
    <div class="star star21"></div>
    <div class="meteor meteor1"></div>
    <div class="meteor meteor2"></div>
    <div class="meteor meteor3"></div>
    <div class="meteor meteor4"></div>
  </div>
</div>

<style>

.frame {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 400px;
  height: 400px;
  margin-top: -200px;
  margin-left: -200px;
  border-radius: 2px;
  overflow: hidden;
  background: infinite;
  color: #333;
  font-family: 'Open Sans', Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.sky {
  position: absolute;
  top: 50%;
  left: 50%;
  overflow: hidden;
  transform: translate(-50%, -50%);
  width: 300px;
  height: 300px;
  border-radius: 50%;
  background: #2980b9;
  background: -webkit-linear-gradient(to bottom, #2c3e50, #2980b9);
  background: linear-gradient(to bottom, #2c3e50, #2980b9);
}

.star {
  position: absolute;
  width: 1px;
  height: 1px;
  border-radius: 50%;
  background: #fff;
}

.star1 {
  width: 3px;
  height: 3px;
  border-radius: 50%;
  top: 50px;
  left: 100px;
  animation: sparkling 5s linear infinite;
}

.star2 {
  width: 2px;
  height: 2px;
  border-radius: 50%;
  top: 100px;
  left: 50px;
  animation: sparkling 5s linear 0.5s infinite;
}

.star3 {
  top: 190px;
  left: 50px;
  animation: sparkling 5s linear 0.6s infinite;
}

.star4 {
  top: 80px;
  left: 30px;
  animation: sparkling 5s linear 0.7s infinite;
}

.star5 {
  top: 90px;
  left: 120px;
  animation: sparkling 5s linear 0.8s infinite;
}

.star6 {
  top: 120px;
  left: 90px;
  animation: sparkling 5s linear 0.9s infinite;
}

.star7 {
  width: 2px;
  height: 2px;
  border-radius: 50%;
  top: 200px;
  left: 150px;
  animation: sparkling 5s linear 0.1s infinite;
}

.star8 {
  top: 150px;
  left: 130px;
  animation: sparkling 5s linear 0.2s infinite;
}

.star9 {
  top: 200px;
  left: 100px;
  animation: sparkling 5s linear 0.3s infinite;
}

.star10 {
  top: 100px;
  left: 200px;
  animation: sparkling 5s linear 0.4s infinite;
}

.star11 {
  top: 210px;
  left: 250px;
  animation: sparkling 5s linear 0.5s infinite;
}

.star12 {
  width: 2px;
  height: 2px;
  border-radius: 50%;
  top: 240px;
  left: 120px;
  animation: sparkling 5s linear 0.2s infinite;
}

.star13 {
  top: 120px;
  left: 240px;
  animation: sparkling 5s linear 0.4s infinite;
}

.star14 {
  top: 130px;
  left: 200px;
  animation: sparkling 5s linear 0.6s infinite;
}

.star15 {
  top: 50px;
  left: 130px;
  animation: sparkling 5s linear 0.3s infinite;
}

.star16 {
  width: 2px;
  height: 2px;
  border-radius: 50%;
  top: 20px;
  left: 100px;
  animation: sparkling 5s linear 0.7s infinite;
}

.star17 {
  top: 30px;
  left: 150px;
  animation: sparkling 5s linear 0.2s infinite;
}

.star18 {
  top: 40px;
  left: 200px;
  animation: sparkling 5s linear 0.5s infinite;
}

.star19 {
  top: 130px;
  left: 40px;
  animation: sparkling 5s linear 0.6s infinite;
}

.star20 {
  top: 250px;
  left: 170px;
  animation: sparkling 5s linear 0.4s infinite;
}

.star21 {
  top: 180px;
  left: 220px;
  animation: sparkling 5s linear 0.3s infinite;
}

.meteor {
  position: absolute;
  width: 130px;
  height: 3px;
  border-radius: 5px;
  background: url(https://100dayscss.com/codepen/shooting-star.png) center center no-repeat;
  background-size: 100% 100%;
}

.meteor1 {
  top: 40px;
  left: -100px;
  transform: rotate(20deg);
  animation: meteor-animation 10s linear 5s infinite;
}

.meteor2 {
  top: -30px;
  left: -70px;
  transform: rotate(20deg);
  animation: meteor-animation 10s linear 6s infinite;
}

.meteor3 {
  top: 15px;
  left: -80px;
  transform: rotate(20deg);
  animation: meteor-animation 10s linear 7s infinite;
}

.meteor4 {
  top: 60px;
  left: -120px;
  transform: rotate(20deg);
  animation: meteor-animation 10s linear 8s infinite;
}

@keyframes meteor-animation {
  0% {
    transform: translate3d(0, 0, 0) rotate(20deg);
  }

  10%,
  100% {
    transform: translate3d(451px, 164px, 0) rotate(20deg);
  }
}

@keyframes sparkling {

  0%,
  100% {
    opacity: 1;
  }

  50% {
    opacity: 0.5;
  }
}
  
</style>
