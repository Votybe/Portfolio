<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">My project</router-link>
    <router-link to="/about">My skills</router-link>
    <router-link to="/about">Reviews</router-link>
    <router-link to="/about">Contact</router-link>
  </nav>
  <router-view />
</template>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: end;
  color: #2c3e50;
}

nav {
  padding: 30px;
  height: 10vh;
  background-color: #3e4f97;
  a {
    font-weight: bold;
    color: #fff;
    margin: 0 0.5rem;
    text-decoration: none;
    // &:hover {
    //   text-decoration: blue;
    // }
  }
}
</style>
