<template>
  <div class="navbar">
      <div class="navbar-left">
        <img src="../assets/uptimaLogo.svg" alt="" >
      </div>
      <div class="navbar-right">
          <a href="#about">About Us</a>
          <a href="#offer" style="margin: 0 50px">Offer</a>
          <button class="navbar-btn">Get In Touch</button>
      </div>

  </div>
</template>

<script>
export default {
    name: "Navbar",
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,400;0,700;1,400&display=swap');




*, body {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.navbar {
    display: flex;
    justify-content: space-between;
    padding: 60px 90px 0 90px;
    position: relative;
}

.navbar-right > a {
    font-family: 'Noto Sans';
    font-weight: normal;
    font-size: 16px;
    color: #FFFFFF;
}

.navbar-btn {
    width: 154px;
    height: 47px;
    background: #FFFFFF;
    border-radius: 24px;
    font-family: 'Noto Sans';
    font-weight: bold;
    font-size: 14px;
    color: #5051DB;
    border: none;
}



















</style>