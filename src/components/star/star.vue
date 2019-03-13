<template>
    <div class="star" :class="startType">
      <span v-for="itemClass in itemClasses" :class="itemClass" class="star-item"></span>
    </div>
</template>

<script>
  export default {
    props:{
      size: {
        type: Number
      },
      score:{
        type: Number
      }
    }
  }
</script>

<style scoped>

</style>
