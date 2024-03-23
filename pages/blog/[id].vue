<script setup>
const route = useRoute()
const { id } = route.params

</script>

<template>
  <h1>I'm a blog page</h1>
  <div>Post id is {{ route.params.id }}</div>
</template>