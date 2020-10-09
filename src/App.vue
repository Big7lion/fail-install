<template>
  <div id="app">
    <input v-model="message" placeholder="edit me">
    <p>Message is: {{ message }}</p>
    <p><button @click="message='xyx'">set message to xyx</button></p>
  </div>
</template>

<script>


export default {
  name: 'App',
  data(){
    return {
      message:'hi'
    }
  },
  components:{}
};
</script>
