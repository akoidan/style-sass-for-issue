<template>
  <div>
  </div>
</template>
<script lang="ts">

  export default {}
</script>
<style lang="scss" scoped>

  $class-slug: for !default

  @for $i from 1 through 4 {
    .#{$class-slug}-#{$i} {
      width: 60px + $i;
      color: black;
    }
  }


</style>


