<template>
  <div class="clothrack">
    <h1>Get a Trouser Today!</h1>
    <div class="clothes">
    <p><nuxt-link to="/">Go back to the Home page</nuxt-link></p>
    </div>
  </div>
</template>

<script>
export default {
  transition: 'tweakOpacity'
}
</script>

<style>
.tweakOpacity-enter-active, .tweakOpacity-leave-active {
  transition: opacity .40s ease-out;
}

.tweakOpacity-enter, .tweakOpacity-leave-active {
  opacity: 0;
}

.clothrack {
  font-family: 'Indie Flower', cursive;
  padding: 50px;
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.clothes {
  display: flex;
  justify-content: space-evenly;
  flex-wrap: wrap;
  width: 500px;
}

html, body {
font-family: 'Indie Flower', cursive;
  background: #9fdfbf;
  color: #000000;
  width: 100vw;
  height: 100vh;
}

h1 {
  width: 1000px;
  justify-content: center;
  display: flex;
}

a, a:visited {
  color: #ffffff;
  text-decoration: none;
}

</style>