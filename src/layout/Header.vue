<template>
  <header class="header">
    <h1>TodoList</h1>
    <div id="">
      <router-link to="/">Home</router-link>
      <router-link to="/state">State</router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.header {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 10px;
}
.header a {
  color: #fff;
  padding-right: 5px;
}
</style>
