<script setup>
</script>
<template>
  <div class="form">
    <form action="https://formsubmit.co/973cd4c2571691fedf98728fcac72687" method="POST">
      <h3 style="text-align:center">Get in touch!</h3>
      <input type="text" id="name" name="name" placeholder="Name" required>
      <input type="text" id="email" name="email" placeholder="Email" required>
      <input type="text" id="phone" name="phone" placeholder="Phone" required>
      <input type="text" id="message" name="message" placeholder="How can I help you?" required>
      <input type="hidden" name="_next" value="https://1342431.com/">
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_template" value="table">
      <button class="button-86" type="submit">Send</button>
    </form>
  </div>
</template>

<style scoped>

::-webkit-input-placeholder {
  text-align: center;
}

:-moz-placeholder {
  text-align: center;
}
input[type="text"] {
  text-align: center;
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
  padding: 10px;
  margin: 20px 37.5%;
  display: flex;
  align-items: center;
  justify-content: center;
  white-space: nowrap;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  top: 50%
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
