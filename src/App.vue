<template>
  <h1>{{ title }}</h1>
</template>

<script>
  export default{
    data(){
      return{
        title: 'Shopping List'
      }
    }
  }
</script>

<style lang="stylus">
  @import url('https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,600,700');
  // Colors
  color-main = #5ecf43
  // Fonts
  font = 'Source Sans Pro', sans-serif;

  // Reset
  *
    box-sizing: border-box
    margin: 0
    padding: 0

  body
    background: color-main
    color: #fff
    font-family: font
</style>

