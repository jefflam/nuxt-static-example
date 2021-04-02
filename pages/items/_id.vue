<template>
  <p>{{ this.$route.params.id }}</p>
</template>

<script>

export default {
  mounted () {
    console.log(this.$route.params.id)
  }
}
</script>
