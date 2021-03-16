<template>
  <div class="LandingPage">
    <div class="blue-bkgnd"></div>
    <div class="get-started-card"></div>
    <div class="customer-avatar"></div>
    <div class="greeting">
      <p>Welcome to HBFT Online Portal. Let's get started !</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "LandingPage",
};
</script>

<style>
.LandingPage {
  width: 360px;
  height: 610px;
  /* background-color: red; */
  background: #eef7ff 0% 0% no-repeat padding-box;
  position: relative;
}
.blue-bkgnd {
  top: 0px;
  left: -0.1060791015625px;
  width: 360px;
  height: 429px;
  background: transparent
    linear-gradient(16deg, #0059a6 0%, #0072d6 49%, #00559e 100%) 0% 0%
    no-repeat padding-box;
  opacity: 1;
  border-radius: 0px 0px 60px 60px;
  /* z-index: -1; */
  position: absolute;
}

.get-started-card {
  top: 334px;
  left: 20px;
  width: 320px;
  height: 244px;
  background: #ffffff 0% 0% no-repeat padding-box;
  box-shadow: 0px 2px 3px #0000001a;
  border-radius: 5px;
  opacity: 1;
  padding: 0px 20px;
  position: absolute;
}

.customer-avatar {
  position: absolute;
  top: 356px;
  left: 32px;
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
  border-width: 3px;
  border-color: #0059a6;
  border-style: solid;
}
</style>