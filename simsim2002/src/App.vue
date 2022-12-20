<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <h1>{{name}}</h1>
  <h1>{{firstname}}</h1>
  <h1>{{lastname}}</h1>
  <h1>{{age}}</h1>
  <h1>{{tel}}</h1>
  <h1>{{room}}</h1>
  <h1>{{major}}</h1>
  <h1>{{school}}</h1>
</template>

<script>

export default {
  name: 'App',
  data(){
    return{
      name:"sim",
      firstname:"NATTHAPOL",
      lastname:"THANYACHAROEN",
      age:"20",
      tel:"174",
      room:"IT5102",
      major:"information technology",
      school:"lannapoly technical college"
    }
  }
}
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
