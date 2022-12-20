<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <h1>{{name}}</h1>
  <h1>{{firstname}} &nbsp;{{lastname}}</h1>
  <h1>{{ getFullname() }}</h1>
  <h1>{{age}}</h1>
  <h1>{{tel}}</h1>
  <h1>{{room}}</h1>
  <h1>{{major}}</h1>
  <h1>{{school}}</h1>
<h2>{{ pofile[gender] }}</h2>
<ul>
  <li>
    {{ hobby[0] }}
  </li>
  <li>
    {{ hobby[1] }}
  </li>
  <li>
    {{ hobby[2] }}
  </li>
  <li>
    {{ hobby[3] }}
  </li>
  <li>
    {{ hobby[4] }}
  </li>
</ul>
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
      school:"lannapoly technical college",
      hobby:["ดูหนัง","ฟังเพลง","เล่นเกม","ต่อกันดั้ม","นอน"],
      pofile:{ gender:"mile",weight:50,hight:170, statud:false}
    }
  },
  methods:{
    getFullname(){
      return this.firstname + this.lastname
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
