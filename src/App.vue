<template>
  <div>
    {{info}}

  </div>
</template>

<script>
export default {
  name: 'App',
  data: function () {
    return {
      info: ''
    }
  },
  mounted () {
    this.$store.dispatch('')
  }
}
</script>
