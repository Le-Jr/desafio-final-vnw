<script setup>
import banner from "../assets/banner.png";
import card01 from "../assets/card01.png";
</script>

<template>
  <main>
    <section class="banner">
      <img :src="banner" alt="" />
      <h1>PROGRAMAÇÃO</h1>
    </section>
    <h3>Artigos Recomendados</h3>
    <section class="artigos">
      <div class="card">
        <img :src="card01" alt="" />
        <h3>O que é linguagem de programação? Conheça as principais</h3>
        <p>
          Uma das mais populares vertentes da tecnologia da informação, a área
          de...
        </p>
      </div>
      <div class="card">
        <img :src="card01" alt="" />
        <h3>O que é linguagem de programação? Conheça as principais</h3>
        <p>
          Uma das mais populares vertentes da tecnologia da informação, a área
          de...
        </p>
      </div>
      <div class="card">
        <img :src="card01" alt="" />
        <h3>O que é linguagem de programação? Conheça as principais</h3>
        <p>
          Uma das mais populares vertentes da tecnologia da informação, a área
          de...
        </p>
      </div>
      <div class="card">
        <img :src="card01" alt="" />
        <h3>O que é linguagem de programação? Conheça as principais</h3>
        <p>
          Uma das mais populares vertentes da tecnologia da informação, a área
          de...
        </p>
      </div>
      <div class="card">
        <img :src="card01" alt="" />
        <h3>O que é linguagem de programação? Conheça as principais</h3>
        <p>
          Uma das mais populares vertentes da tecnologia da informação, a área
          de...
        </p>
      </div>
      <div class="card">
        <img :src="card01" alt="" />
        <h3>O que é linguagem de programação? Conheça as principais</h3>
        <p>
          Uma das mais populares vertentes da tecnologia da informação, a área
          de...
        </p>
      </div>
    </section>
  </main>
</template>

<style scoped lang="scss">
.banner {
  position: relative;
  h1 {
    color: white;
    font-weight: 700;
    position: absolute;
    top: 150px;
    left: 600px;
  }
  img {
    width: 100%;
    height: 100%;
  }
  width: 100%;
}

.artigos {
  margin-top: 3em;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;

  gap: 2em;

  .card {
    border: solid 1px black;
    img {
      width: 100%;
    }
    width: 30%;
    height: 50%;
  }
}
</style>
