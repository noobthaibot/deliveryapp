<template>
  <div id="nav">
    <router-link to="/">Меню</router-link>
    |
    <router-link to="/about">Доставка и оплата</router-link>
    |
    <router-link to="/products">Контакты</router-link>
    |
    <router-link to="/login">Вход</router-link>
  </div>
  <router-view />
</template>

<script>
export default {
  name: "App",
  components: {
    
  },
};
</script>

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
  color: #545454;
}
</style>
