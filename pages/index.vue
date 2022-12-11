<template>
  <div>
    <ul class="nav">
      <li class="nav-item">
        <NuxtLink class="nav-link active" aria-current="page" to="https://github.com/nuxt">Активная</NuxtLink>
      </li>
      <li class="nav-item">
        <NuxtLink class="nav-link" to="/about/About">About</NuxtLink>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Ссылка</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Отключенная</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "index"
}
</script>

<style scoped>

</style>