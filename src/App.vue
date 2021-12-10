<template>
  <div id="app">
    <Title />
    <Hero />
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    Title,
    Hero,
  },
};
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

@font-face {
  font-family: "Orbitron";
  src: local("Orbitron"),
    url(./fonts/Orbitron/Orbitron-Regular.ttf) format("truetype");
}

body {
  background-color: rgb(26, 26, 26);
  font-family: "Orbitron", sans-serif;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
