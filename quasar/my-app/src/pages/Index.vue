<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    >
     <p v-for="i in 20" :key="i">
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Repellendus
      ratione atque asperiores, sunt veritatis consequuntur sit consectetur odit
      corrupti optio velit saepe laborum cupiditate, in neque nemo molestiae at
      error?
    </p>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'PageIndex'
})
</script>
