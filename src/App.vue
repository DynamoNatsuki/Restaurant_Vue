<template>
  <nav>
    <router-link to="/">Start</router-link> |
    <router-link to="/menu">Lunchmeny</router-link> |
    <router-link to="/about">Kontakta oss</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background: lightblue;
  padding: 100px;
}

ul{
  list-style-type: none;
}

li{
  padding: 10px;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
