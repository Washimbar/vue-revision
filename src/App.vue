<template>
  <div>
    <h1>Hello {{ name }}</h1>
  </div>
</template>

<script>
export default {
  name: 'App',
  setup() {
    return {
      name: 'Washim Bari',
    }
  }
}
</script>

<style lang="scss" scoped></style>
