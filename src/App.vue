<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
  components: {
    AppTitle,
    AppHero,
  }
}
</script>

<template>
  <div>
    <AppTitle />
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Explicabo minus autem dolorem, inventore cum quae doloremque nesciunt excepturi delectus quis pariatur aperiam nulla blanditiis rerum dolore nobis eveniet odit tempore?</p>
    <AppHero />

  </div>
</template>

<style scoped>


p{
  background-color: red;
}
</style>
