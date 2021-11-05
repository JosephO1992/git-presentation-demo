<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
                                                                    </script>

<template>
  <div class="container">
    <img alt="Vue logo" src="./assets/nimbus-hosting.svg" />
    <HelloWorld msg="Hey Nimbus Team! On a new-branch" />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
}
img {
  height: 5rem;
}
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-items: center;
  height: 100vh;
  justify-content: center;
}
</style>
