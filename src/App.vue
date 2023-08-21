<script>
import Title from "./components/apptitle.vue"
import Hero from "./components/AppHero.vue"
export default {
  components: {
    Title,
    Hero,
  }
}
</script>

<template>
<Title/>
<Hero/>

</template>

<style>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>