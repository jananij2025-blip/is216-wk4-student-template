<script setup>
import { ref } from 'vue'
import me from '/assets/me.png'
// Add code here
const width= ref('200')
const height= ref ('200')
const myImg= ref ('/assests/me.png')

const obj=ref({
  width: '200',
  height: '200',
  src: '/assests/me.png'
})
</script>

<template>
  <!-- Add code here -->
   
  <img v-bind:src="myImg" :width="width" :height="height"/>
  <img v-bind="obj">
  

</template>
