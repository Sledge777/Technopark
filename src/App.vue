<template>
  <the-header/>
  <p>направления</p>
  <section class="chose">
    <div class="chose__wrapper">
      <img class="chose__wrapper__img" src="@/assets/webdev.jpg" alt="">
      <div class="btn"></div>
      <div class="btn2"></div>
    </div>
  </section>
</template>

<script>
import TheHeader from './components/TheHeader.vue'

export default {
  name: 'App',
  components: {
    TheHeader
  }
}
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
body {
  background-color: black;
}
.chose {
  width: 50%;
  margin: auto;
}
.chose__wrapper {
  position: relative;
}
.chose__wrapper__img {
  width: 100%;
  border-radius: 50px;
}
.btn {
  height: 30px;
  width: 30px;
  background-color: black;
  position:absolute;
  border-radius: 100%;
  bottom:10px;
  right: 20px;
}
.btn2 {
  height: 30px;
  width: 30px;
  background-color: black;
  position:absolute;
  border-radius: 100%;
  bottom:10px;
  right: 60px;
}
.btn2:hover, .btn:hover {
  background-color: grey;
  transition: all 0.3s;
  cursor: pointer;
}
</style>
