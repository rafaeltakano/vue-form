<template>
  <nav id="nav-bar">
    <router-link to="/">Home</router-link> |
    <router-link to="/form">Form</router-link>
  </nav>
</template>

<style scoped>
nav {
  padding: 30px;
  text-align: center;
}

nav a {
  font-weight: bold;
}

nav a.router-link-exact-active {
  color: var(--color-primary);
}
</style>
