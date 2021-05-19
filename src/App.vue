<template>
  <div id="app">

    <Title/>

    <Hero/>
    
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import Title from './components/Title.vue'




export default {
  name: 'App',
  components: {
    Title,
    Hero
    
    
  }
}
</script>

<style lang="scss">

</style>
