<template>
  <div id="app">
    <h1>{{title}}</h1> 
    <Intro />
  </div>
</template>

<script>
import Intro from "./BaseComponent.vue";

export default {
  components: {
    Intro
  },
  setup () {
    return {title: "Hello Human!"}
  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Noto+Serif&display=swap');

html, body, h1, h2, h3, p {
  font-family: 'Noto Serif', serif;
  user-select: none;
}

#app {
  text-align: center;
  color: rgba(0,0,0,0.4);
}
img {
  width: 500px;
}
a {
  color: #41b883;
  text-decoration: none;
  cursor: pointer;
}
</style>
