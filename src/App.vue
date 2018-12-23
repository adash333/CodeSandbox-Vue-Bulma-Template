<template>
  <div id="app">
    <nav class="navbar has-background-info">
      <div class="navbar-brand">
        <a class="navbar-item has-text-white" href="#"> Bulmaテンプレート </a>
      </div>
    </nav>

    <section class="section">
      <div class="container"><!-- ここにコンテンツを記載 --></div>
    </section>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>

<style></style>
