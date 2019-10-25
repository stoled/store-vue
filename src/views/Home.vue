<template>
  <div>
    <Hero />
    <b-container>
      <Cards />
    </b-container>
  </div>
</template>

<script>
import Hero from '@/components/Hero.vue'
import Cards from '@/components/Cards.vue'

export default {
  components: {
    Hero,
    Cards
  }
}
</script>