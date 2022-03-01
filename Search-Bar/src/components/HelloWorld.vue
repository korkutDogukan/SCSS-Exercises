<template>
  <div class="searchbar-container">
    <form class="searchbar-container-form" action="https://www.google.com/search" method="get">
      <input
        type="text"
        placeholder="search anything"
        name="q"
        class="searchbar-container-form-input"
      />
      <button type="submit" class="searchbar-container-form-button">
        <img src="../assets/images/search.png" />
      </button>
    </form>
  </div>
</template>
<script setup>
</script>
<style src="./HelloWorld.scss" lang="scss">
</style>