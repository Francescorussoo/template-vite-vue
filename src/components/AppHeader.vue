<script>
export default {
  data() {
    return { 
      message: 'Template Vite + Vue'
    }
  }
}
</script>

<template>
  <header>
    <h1>
      {{ message }}
    </h1>
  </header>
</template>

<style scoped>
header {
  background-color: aquamarine;
  text-align: center;
  padding: 20px 0;
}

h1 {
  color: lightcoral;
}
</style>
