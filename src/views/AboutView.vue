<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>

<script>
export default {
  data() {
    return {
      data: {},
    }
  },
  mounted() {
    console.log(import.meta.env.VITE_TEXT)
    console.log(import.meta.env.VITE_PATH)
    // const url = import.meta.env.VITE_PATH
  },
}
</script>
