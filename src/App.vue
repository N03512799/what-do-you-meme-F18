<template>
  <div id="app" class="container">
    <img alt="Vue logo" src="../assets/logo.png">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
@import "../node_modules/bootstrap/scss/bootstrap.scss";
</style>
