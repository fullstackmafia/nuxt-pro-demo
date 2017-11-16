<template>
  <div class="clothrack">
    <h1>Get a Shirt Today!</h1>
    <div class="clothes">
    <p><nuxt-link to="/">Go back to the Home page</nuxt-link></p>
    </div>
  </div>
</template>

<style scoped>
.page-enter-active {
  animation: acrossIn .40s ease-out both;
} 

.page-leave-active {
  animation: acrossOut .60s ease-in both;
} 

@keyframes acrossIn {
  0% {
    transform: translate3d(-100%, 0, 0);
  }
  100% {
    transform: translate3d(0, 0, 0);
  }
}

@keyframes acrossOut {
  0% {
    transform: translate3d(0, 0, 0);
  }
  100% {
    transform: translate3d(100%, 0, 0);
  }
}

.clothrack {
  font-family: 'Indie Flower', cursive; 
  padding: 50px;
  width: 100vw;
  height: 100vh;
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


<style scoped>
  .clothrack {
    color: #595959;
  }
</style>
