<script setup>
import logo from "../assets/logo.png";
</script>

<template>
  <header>
    <img :src="logo" alt="Logo do site" />
    <nav>
      <ul>
        <li>Início</li>
        <li>Artigos</li>
      </ul>
    </nav>
  </header>
</template>

<style scoped lang="scss">
header {
  width: 100%;
  /* border: red solid 1px; */
  height: 5rem;
  font-family: "Inter", sans-serif;
  font-weight: 700;
  font-size: 1rem;
  padding: 0 10%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  img {
    /* width: 60px; */
    height: 30px;
  }
  nav {
    width: 200px;
    /* border: solid blue 5px; */
  }
  ul {
    /* border: red solid 1px; */
    width: 100%;
    display: flex;
    justify-content: space-around;
    gap: 1em;
    list-style: none;
  }
}
</style>
