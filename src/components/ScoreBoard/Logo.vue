<template>
  <h1 class="logo">
    <a href="#" target="_blank">REFRESH</a>
  </h1>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
  name: 'Logo'
})
</script>

<style scoped>
.logo {
  width: 160px;
  height: 100px;
  line-height: 90px;
  padding: 5px;
  border-radius: 5px;
  background-color: #5979ac;
  color: #fff;
  text-align: center;
  font-family: 'Syne Tactile', cursive;

  @import url('https://fonts.googleapis.com/css2?family=Syne+Tactile&display=swap');
}
a {
  text-decoration: none;
  color: #fff;
}

@media screen and (max-width: 450px) {
  .logo {
    width: 150px;
  }
}

@media screen and (max-width: 380px) {
  .logo {
    width: 140px;
  }
}

@media screen and (max-width: 360px) {
  .logo {
    width: 110px;
  }
  a {
    font-size: 18px;
  }
}
</style>
