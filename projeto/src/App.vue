<template>
  <div id="app">
    <TheHeader />
    <main id="main">
      <transition mode="out-in">
      <router-view />
      </transition>
    </main>

  </div>
</template>
<script>
import TheHeader from "@/components/TheHeader.vue";


export default {
  components: {
    TheHeader
  },
};
</script>
<style>
* {
  box-sizing: border-box;
}
body,
ul,
li,
h1,
h2,
p {
  padding: 0px;
  margin: 0px;
}
ul {
  list-style-type: none;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 0px 20px;
  max-width: 1200px;
      
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
