<template>
  <div>
    <NuxtLink to="/flights">
      <q-btn color="white" text-color="black" label="Flight" />
    </NuxtLink>
    <NuxtLink to="/trains">
      <q-btn color="primary" label="Train" />
    </NuxtLink>

    <h1>Welcome to 2024 ...</h1>
    <Search />
  </div>
</template>

<script setup>
const route = useRoute();
console.log(route);
</script>
