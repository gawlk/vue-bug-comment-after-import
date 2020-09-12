<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
</template>

<script setup>
import mediasoup from 'mediasoup-client' // remove this comment and it'll work

import HelloWorld from './components/HelloWorld.vue'

// import mediasoup from 'mediasoup-client' // Here is works even with the comment

export default {
  components: {
    HelloWorld
  }
}
</script>
