<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p-4">
        <NuxtLink class="font-bold" to="/products">Dojo Merch</NuxtLink>
      </nav>
    </header>
    <div class="container mx-auto p-4">
      <slot></slot>
    </div>
    <footer class="container mx-auto p-4 flex justify-between border-t-2">
      <ul class="flex gap-4">
        <li>
          <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about">About</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/products">Products</NuxtLink>
        </li>
      </ul>
    </footer>
  </div>
</template>

<script setup></script>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>
