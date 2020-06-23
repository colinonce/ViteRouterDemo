<template>
  <div>user: {{ id }}</div>
</template>

<script>
export default {
  name: 'user',
  props: {
    id: String
  },
  setup (...args) {
    console.log(args)
  }
}
</script>
