<template>
  <div id="nav">
    <router-link to="/">Twitter Clone</router-link> | 
    <router-link to="/about">About Us</router-link> |  
    <router-link to="/contact">Contact Us</router-link> 
  </div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #2aa9e0;
}
</style>
