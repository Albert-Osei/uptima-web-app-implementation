<template>
  <div class="footer-section">
    <div class="footer-content">
      <div class="footer-flexbox">
        <div class="footer-flexitem1">
          <h3 class="footer-header">Contact Us</h3>
          <div class="footer-anchor">
            <a style="max-width: 172px">24 Oluloye estate, Ibadan, Oyo state.</a>
            <a>Uptime.ng</a>
            <a>info@uptima.ng</a>
            <a>08140710074</a>
          </div>
        </div>
        <div class="footer-flexitem2">
          <h3 class="footer-header">Social Media</h3>
          <div class="footer-icon-group">
            <div class="footer-icon">
              <img src="../assets/twitter.svg" alt="" />
            </div>
            <div class="footer-icon">
              <img src="../assets/facebook.svg" alt="" />
            </div>
            <div class="footer-icon">
              <img src="../assets/instagram.svg" alt="" />
            </div>
            <div class="footer-icon">
              <img src="../assets/Linkedin.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
      <div class="copyright">
        <div class="footer-logo">
          <img src="../assets/footerLogo.svg" alt="" />
        </div>
        <p class="copyright-text">Copyright@2020 Uptima</p>
        <p class="copyright-text">Privacy & Policy</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,400;0,700;1,400&display=swap');


*, body {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.footer-section {
  width: 100%;
  background: #5051DB;
}

.footer-content {
  padding: 66px 91px 62px 91px;
}

.footer-flexbox {
  display: flex;
  justify-content: space-between;
  margin-bottom: 24px;
}

.footer-flexitem2 {
  margin-right: 382px;
}

.footer-header {
  font-family: 'Noto Sans';
  font-weight: 600;
  font-size: 20px;
  color: #FFFFFF;
}

.footer-anchor {
  font-family: 'Noto Sans';
  font-weight: normal;
  font-size: 14px;
  color: #FFFFFF;
  display: flex;
  flex-direction: column;
}

.footer-anchor > a {
  margin-top: 16px;
}

.footer-icon-group {
  display: flex;
  margin-top: 22px;
}

.footer-icon {
  width: 25px;
  height: 25px;
  margin-right: 14px;
}

.footer-icon img {
  width: 100%;
  height: 100%;
}

.copyright {
  border-top: 2px solid #FFFFFF;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-top: 35px;
}

.copyright-text {
  font-family: 'Noto Sans';
  font-weight: normal;
  font-size: 14px;
  color: #FFFFFF;
}


@media screen and (max-width: 768px) {
  .footer-content {
    padding: 0;
  }

  .footer-flexbox {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
  }

  .footer-flexitem2 {
    margin-right: 0;
  }

  .copyright {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
  }
}
</style>