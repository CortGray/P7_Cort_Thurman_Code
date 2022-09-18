<template>
  <div id="app">
    <nav>
      <img alt="Groupomania logo" src="@/assets/icon-left-font.png">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #000;

    &.router-link-exact-active {
      color: #FD2D01;
    }
  }
}
</style>
