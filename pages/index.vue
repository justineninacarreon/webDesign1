<template>
  <div id="home-page">
    <TheHeader />
    <hero />
    <downarrow />
  </div>
</template>

<script>

import TheHeader from "~/components/TheHeader.vue"
import hero from "~/components/hero"
import downarrow from "~/components/downarrow"
export default{
  name: "HomePage",
  components: {
    TheHeader,
    hero,
    downarrow
  }
}
</script>

<style>

</style>

