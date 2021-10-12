<template>
  <main>
    <h1 style="text-align: center; margin: 40px">
      Convert LaTeX to Moodle styled LaTeX
    </h1>
    <Body />
  </main>
</template>

<script>
import Body from "./components/Body.vue";

// title
document.title = "LaTeX to Moodle Converter";

export default {
  name: "LaTeX to Moodle Converter",
  components: {
    Body,
  },
};
</script>

<style>
body {
  margin: 0;
  background-color: beige;
}
main {
  margin: 0 auto;
  padding: 50px;
  max-width: 960px;
  min-height: 100vh;
  background-color: rgb(255, 255, 255);
}
p {
  margin: 10px;
  margin-left: 0;
}

.copyButton {
  text-align: right;
}
</style>
