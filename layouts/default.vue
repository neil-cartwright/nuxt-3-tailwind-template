<template>
 <div>
  <header>
   <nav>
    <ul class="flex max-w-5xl mx-auto bg-blue-500 p-2 text-white gap-8">
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
   </nav>
  </header>
  <div class="max-w-5xl mx-auto">
   <slot />
  </div>
 </div>
</template>

<script setup></script>

<style scoped>
.router-link-exact-active {
 color: orange;
}
</style>
