<template>
  <header class="global-header">
    <div class="row">
      <div class="global-logo">
        <a href="/">Vue KendoUI</a>
      </div>
      <Navbar />
    </div>
  </header>
  <router-view />
  <Footer />
</template>

<script>
import Navbar from "./components/Navbar";
import Footer from "./components/Footer";

export default {
  name: "app",
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: "Montserrat", sans-serif;
  -webkit-font-smoothing: antialiased;
}

body {
  background: #28282b;
}

.global-header {
  position: fixed;
  top: 0;
  width: 100%;
  background: #fff;
  z-index: 999;
}

.row {
  display: flex;
  align-items: center;
  height: 80px;
  padding: 0;
  max-width: 1000px;
  margin: 0 auto;
}

.global-logo a {
  color: #252222;
  text-decoration: none;
  font-size: 24px;
  font-weight: bold;
}
</style>
