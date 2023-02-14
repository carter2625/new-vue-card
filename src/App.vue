<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <div class="card">
  <h1 class="h1">Philadelphia 76ers</h1>
  <img class="player" src="https://cdn.nba.com/teams/legacy/www.nba.com/sixers/sites/sixers/files/getty-images-1238023470.jpg" alt="Maxey">
  <div class="container">
    <h4 class="h1"><b>Tyrese Maxey, PG</b></h4>
    <p class="p1">Tyrese Kendrid Maxey, nicknamed "Mad Maxey", is an American professional basketball player for the Philadelphia 76ers of the National Basketball Association.</p>
    <button class="info">Details</button>
    </div>
</div>

  <button class="add">Clone The Card </button>
    <button class="changeBC">Change Background</button>
    <button class="changeH">Change Heading</button>
    <button class="delete">Delete Clone</button>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  border-radius: 5px;
  background-color: red;
  
  
  
 
  
}

.h1{
  text-align: center;
  color: white;
}


.p1{
  text-align: center;
  color: white;
  
}



button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: blue;
  text-align: center;
  cursor: pointer;
  width: 22%;
  font-size: 15px;
  margin: 8px 4px;
  
}

.info {
        background-color: #1c87c9;
        border: none;
        color: white;
        padding: 10px 25px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 15px;
        margin: 10px 160px;
        cursor: pointer;
      }

  .player{
    max-width: 100%;
    height: auto;
  }



button:hover, a:hover, button:focus {
  opacity: 0.7;
}
</style>
