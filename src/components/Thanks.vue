<script setup>
</script>
<template>
  <div class="thanks_div">
    <h1 class="thanks">Thank you!!</h1>
    <h3 class="thanks_2">We will reach out to you shortly.</h3>
  </div>
  <div class="contact_button_css">
    <button class="button-86" role="button" @click="$router.push('/')">Home</button>
  </div>
</template>
<style scoped>
.thanks{
  text-align: center;
  color: #ffffff;
}
.thanks_2{
  text-align: center;
  color: #c18d71;
}
.thanks_div {
padding: 180px 0 20px 0;
}

.contact_button_css{
  margin: 0 37.5%;
  position: relative;
}

  .button-86 {
  all: unset;
  width: 100px;
  height: 30px;
  font-size: 16px;
  background: transparent;
  border: none;
  position: relative;
  color: #f0f0f0;
  cursor: pointer;
  z-index: 1;
  padding: 10px 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  white-space: nowrap;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
}

.button-86::after,
.button-86::before {
  content: '';
  position: absolute;
  bottom: 0;
  right: 0;
  z-index: -99999;
  transition: all .4s;
}

.button-86::before {
  transform: translate(0%, 0%);
  width: 100%;
  height: 100%;
  background: #051e28;
  border-radius: 10px;
}

.button-86::after {
  transform: translate(10px, 10px);
  width: 35px;
  height: 35px;
  background: #c18d71;
  backdrop-filter: blur(5px);
  -webkit-backdrop-filter: blur(5px);
  border-radius: 50px;
}

.button-86:hover::before {
  transform: translate(5%, 20%);
  width: 110%;
  height: 110%;
}

.button-86:hover::after {
  border-radius: 10px;
  transform: translate(0, 0);
  width: 100%;
  height: 100%;
}

.button-86:active::after {
  transition: 0s;
  transform: translate(0, 5%);
}
</style>
