<template>
  <h1 class="title">Hello Vue</h1>
  <ul>
    <li><router-link to="/home">Home</router-link></li>
    <li><router-link to="/about">About</router-link></li>
  </ul>
  <router-view/>
</template>
    
<script>
import Home from "./views/Home";
export default {
  name: "App"
};
</script>
    
<style>
.title {
  color: aqua;
}
</style>