<template>
  <router-view/>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Reggae+One&display=swap');

  body {
    background: #f3f3f3;
    font-family: 'Reggae One', cursive;
  }

  ::selection {
    background: black;
    color: #fff;
  }

  *:focus {
    outline: none;
  }

  button, a {
    cursor: pointer;
  }
</style>
