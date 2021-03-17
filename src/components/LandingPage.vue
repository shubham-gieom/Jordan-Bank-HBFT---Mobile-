<template>
  <!-- <v-app> -->
  <div class="LandingPage">
    <div class="blue-bkgnd"></div>
    <div class="scroll">
      <div class="hbtflogo">
        <img src="../assets/Jordan Bank HBFTlogo.png" />
      </div>
      <div class="landingpage-image">
        <img src="../assets/jordan-bank-hbft-2.png" alt="landingpage-Image" />
      </div>

      <div class="language-title">
        <p>Please switch to your preferred language</p>
        <div class="language-switch">
          <p>English</p>
          <div class="toggle-switch">
            <v-switch
              v-model="ex11"
              inset
              color="white"
              value="عربى"
            ></v-switch>
          </div>
          <p>عربى</p>
        </div>
      </div>

      <div class="get-started-card">
        <div class="greeting-section">
          <div class="customer-avatar"></div>
          <div class="greeting">
            Welcome to HBFT Online Portal. Let's get started !
          </div>
        </div>
        <v-divider></v-divider>
        <div class="spacing">
          <button class="new-customer">
            <div class="customer-icon-box">
              <div class="icon-circle"></div>
            </div>
            <div class="customer-type-box">New Customer</div>
            <div class="arrowsymbol">-></div>
          </button>
        </div>
        <v-divider></v-divider>
        <div class="spacing">
          <button class="existing-customer">
            <div class="customer-icon-box">
              <div class="icon-circle"></div>
            </div>
            <div class="customer-type-box">Existing Customer</div>
            <div class="arrowsymbol">-></div>
          </button>
        </div>
        <v-divider></v-divider>
        <div class="spacing">
          <div class="help">Need help ?</div>
        </div>
      </div>

      <div class="isken-coin-ad">
        <button class="close">x</button>
      </div>
      <div class="footer">
        <p class="copyright">2020 Copyright| Terms & Conditions</p>
      </div>
    </div>

    <!-- <div class="customer-avatar"></div> -->
  </div>
  <!-- </v-app> -->
</template>

<script>
export default {
  name: "LandingPage",
};
</script>

<style>
.hbtflogo {
  position: relative;
  top: 30px;
  /* left: 104px; */
  width: 152px;
  height: 45px;
  margin-left: 50px;
  /* background-color: red; */
}
.landingpage-image {
  position: relative;
  top: 106px;
  /* left: 47px; */
  width: 150px;
  /* height: 130px; */
  opacity: 1;
  margin: 0px 26.95px;
  /* background-color: red; */
}
.language-switch {
  position: relative;
  left: 50px;
  top: -25px;
  /* margin-left: 85px; */
  display: flex;
  /* background-color: yellow; */
}
.language-switch > p {
  position: relative;
  top: 8px;
  text-align: left;
  font: normal normal medium 14px/17px Inter;
  letter-spacing: 0px;
  color: #ffffff;
  opacity: 1;
}
.toggle-switch {
  margin-left: 10px;
}

.language-title {
  position: relative;
  top: 133px;
  /* left: 64px; */
  width: 240px;
  height: 15px;
  text-align: center;
  font: normal normal normal 12px/15px Inter;
  letter-spacing: 0px;
  color: #ffffff;
  opacity: 1;
  margin: 0px 40px;
  /* background-color: green; */
}
.close {
  position: relative;
  top: 3px;
  left: 292px;

  width: 19px;
  height: 19px;
  border-radius: 50%;
  text-align: center;
  align-items: center;
  font-size: 10px;
  color: white;
  background-color: #3370a5;
}
.copyright {
  text-align: center;
  background: #ffffff1f 0% 0% no-repeat padding-box;
  opacity: 1;
}
.footer {
  position: relative;
  top: 228px;
  width: 320px;
  height: 47px;
  background: #ffffff 0% 0% no-repeat padding-box;
  opacity: 1;
  /* background-color: red; */
  border-radius: 2px;
  padding: 17.43px 0.2px 10px 6.69px;
}
.isken-coin-ad {
  position: relative;
  top: 218px;
  width: 320px;
  height: 122px;
  /* background: #ffffff 0% 0% no-repeat padding-box; */
  box-shadow: 0px 2px 3px #0000001a;
  border-radius: 5px;
  opacity: 1;
  background-color: #0059a6;
}
.icon-circle {
  width: 22px;
  height: 22px;
  border: 1px solid #3370a5;
  border-radius: 50%;
  opacity: 1;
}
.arrowsymbol {
  margin-left: 91px;
  width: 19px;
  height: 19px;
  border-radius: 50%;
  opacity: 1;
  color: white;
  background-color: #0059a6;
}
.customer-type-box {
  margin-left: 10px;
  width: 131px;
  height: 19px;
  text-align: left;
  font: normal normal medium 15px/19px Inter;
  letter-spacing: 0px;
  color: #004d8f;
  opacity: 1;
}
.customer-icon-box {
  width: 35px;
  height: 32px;
  background: #eef5fa 0% 0% no-repeat padding-box;
  border-radius: 3px;
  padding: 5px 6px 5px 7px;
  opacity: 1;
}

.LandingPage {
  position: absolute;
  top: 0px;
  width: 360px;
  height: 120vh;
  background: #eef7ff 0% 0% no-repeat padding-box;
  opacity: 1;
  /* background-color: red; */
  /* z-index: -1; */
}
.blue-bkgnd {
  position: fixed;
  top: 0px;
  /* left: -0.1060791015625px; */
  width: 360px;
  height: 429px;
  background: transparent
    linear-gradient(16deg, #0059a6 0%, #0072d6 49%, #00559e 100%) 0% 0%
    no-repeat padding-box;
  opacity: 1;
  border-radius: 0px 0px 60px 60px;
  /* z-index: -1; */
  /* position: absolute; */
}

.scroll {
  position: absolute;
  margin: 2px 20px 0px 20px;
  /* top: 2px;
  left: 20px; */
  width: 320px;
  /* height: 638px; */
  mix-blend-mode: normal;
  opacity: 1;
  /* background-color: red; */
}

.logo {
  position: relative;
  top: 30px;
  left: 104px;
  width: 152px;
  height: 45px;
  background: transparent url("") 0% 0% no-repeat padding-box;
  opacity: 1;
  background-color: blue;
}

.get-started-card {
  top: 194px;
  /* left: 20px; */
  width: 320px;
  height: 244px;
  background: #ffffff 0% 0% no-repeat padding-box;
  box-shadow: 0px 2px 3px #0000001a;
  border-radius: 5px;
  opacity: 1;
  /* padding: 0px 20px; */
  position: relative;
}
.greeting-section {
  display: flex;
  padding: 19.72px 0px 19.72px 10.33px;
}

.customer-avatar {
  /* position: absolute; */

  width: 38px;
  height: 38px;
  background: transparent
    radial-gradient(
      closest-side at 50% 50%,
      #e7f4ff 0%,
      #d3eaff 47%,
      #afd9ff 100%
    )
    0% 0% no-repeat padding-box;
  opacity: 1;
  border-radius: 50%;
  border-width: 2px;
  border-color: #0059a6;
  border-style: solid;
}
.greeting {
  margin-left: 10.16px;
  width: 230px;
  height: 49px;
  text-align: left;
  font: normal normal normal 15px/25px Inter;
  letter-spacing: 0px;
  color: #3d3d3d;
  opacity: 1;
}
.spacing {
  padding: 10px 0px;
}
.new-customer {
  /* position: relative; */
  /* top: 425px; */
  /* left: 20px; */
  display: flex;
  width: 286px;
  height: 32px;
  margin: 0px 20px 0px 14px;
  /* width: 320px;
  height: 50px; */
  box-shadow: 0px 0px 3px #0000001a;
  border-radius: 5px;
  opacity: 1;
  /* background-color: lightgreen; */
}
.existing-customer {
  /* position: absolute; */
  /* top: 480px; */
  /* left: 20px; */
  /* width: 320px;
  height: 50px; */
  display: flex;
  width: 286px;
  height: 32px;
  margin: 0px 20px 0px 14px;
  /* background: #ffffff 0% 0% no-repeat padding-box; */
  /* background-color: pink; */
  box-shadow: 0px 0px 3px #0000001a;
  border-radius: 5px;
  opacity: 1;
}

.help {
  /* left: 141px; */

  width: 79px;
  height: 17px;
  text-align: center;
  font: normal normal normal 14px/17px Inter;
  letter-spacing: 0px;
  color: #7d7d7d;
  opacity: 1;

  margin: 0px 120px 13px 121px;
}
</style>