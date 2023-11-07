<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>

<template>
  <div class="wrapper">
    <header>
      <section class="header">
        <h1 class="header__title">Urbo Coffee</h1>
      </section>
    </header>

    <RouterView></RouterView>
  </div>
</template>

<style scoped lang="scss">
.wrapper {
  max-width: 768px;
  background-color: #ebebeb;
  margin: 0px auto;
}

.header {
  padding: 20px 0px;
}

.header__title {
  font-family: 'Raleway', sans-serif;
  font-weight: 900;
  font-size: 18px;
  text-align: center;
  letter-spacing: .4px;
}
</style>
