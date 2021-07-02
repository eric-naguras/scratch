<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Hello Vue 3 + Vite" />
    <p v-for="i in 20" :key="i">
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Repellendus
      ratione atque asperiores, sunt veritatis consequuntur sit consectetur odit
      corrupti optio velit saepe laborum cupiditate, in neque nemo molestiae at
      error?
    </p>
  </div>
</template>

<script setup>
  import HelloWorld from './components/HelloWorld.vue'

  // This starter template is using Vue 3 experimental <script setup> SFCs
  // Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
