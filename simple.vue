<template>
  <div>
      <p class="simple">Hello From Component in {{location}}</p>
  </div>
</template>

<script>
export default {
  data: function() {
      return {
          location: "node_modules"
      }
  }
}
</script>

<style>
.simple {
    color: blue;
    text-decoration: underline;
}
</style>
