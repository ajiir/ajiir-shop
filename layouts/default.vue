<template>
  <div>    
    <client-only>
      <top-bar />
      <main-header />
        <nuxt />
      <main-footer />
    </client-only>
  </div>
</template>

<script>
import mainHeader from '../components/mainHeader'
import mainFooter from '../components/mainFooter'
import topBar from '../components/topBar'
export default {
  name: 'Default',
  components: {
    mainHeader,
    mainFooter,
    topBar
  },
}
</script>

<style>

</style>