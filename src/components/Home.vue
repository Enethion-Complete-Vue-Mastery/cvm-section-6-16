<template>
  <h1>
    Home
  </h1>
</template>

<script>
export default {
  unmounted () {
    console.log('Home component was unmounted')
  },
  activated () {
    console.log('Home component was activated')
  },
  deactivated () {
    console.log('Home component was deactivated')
  }
}
</script>
