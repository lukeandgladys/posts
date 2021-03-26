<template id="">
  <header>
    <NuxtLink to="/" >index</NuxtLink>
    <NuxtLink to="/about" >about</NuxtLink>
    <NuxtLink to="/posts" >posts</NuxtLink>

  </header>

</template>
<script>

</script>

<style scoped>
  header {
    display: flex;
    width: 100%;
    justify-content: space-between;
    flex-wrap: wrap;
  }
  header a {
    font-size: 2em;
    font-variant: small-caps;
    flex: 1 1 20%;
    text-decoration: none;
    color: #000;
  }

</style>
