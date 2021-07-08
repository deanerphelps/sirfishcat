<template>
<header class="navbar">
  <img alt="CoatOfFish" src="../assets/CoatOfFish.png" class="coat">
    <div class="buttons">
      <button @click="$router.push('/')" class="button is-link is-outlined">Home</button>
      <button @click="$router.push('/Ina')" class="button is-link is-outlined">Ina</button>
      <button @click="$router.push('/About')" class="button is-link is-outlined">About</button>
    </div>
</header>
<br />
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.coat {
  height: 200px;
  padding: 10px;
}
button {
  width: 100px;
  margin-left: 30px;
}
.buttons {
  margin-left: 60%;
  margin-top: 2%;
  display: inline-block;
}
.navbar {
  background-color: lightgray;
}
</style>
