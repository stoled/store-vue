<template>
  <div id="app">
    <NavBar />
    <main>
      <router-view/>
    </main>
  </div>
</template>

<script>
  import NavBar from '@/components/NavBar.vue'

  export default {
    components: {
      NavBar
    }
  }
</script>

<style lang="scss">
  main {
    padding-top: 56px;
  }
</style>
