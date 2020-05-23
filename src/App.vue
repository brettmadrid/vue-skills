<template>
  <div id="app">
    <!-- Can pass in props to component ala React -->
    <Skills />
  </div>
</template>

<script>
import Skills from "./components/Skills.vue";

export default {
  name: "App",

  // components used in app
  components: {
    Skills
  }
};
</script>

// in app.vue, global styles can be put here
<style>
@import url("https://fonts.googleapis.com/css?family=Montserrat:400,700");

body {
  background-color: #eeeeee;
  font-family: "Montserrat", sans-serif;
  display: grid;
  grid-template-rows: auto;
  justify-items: center;
  align-items: center;
}
body,
html {
  margin: 0;
  height: 100%;
}
#app {
  width: 50%;
}
</style>
