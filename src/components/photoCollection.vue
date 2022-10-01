<template>
  <div class="collection">
    <img class="collection__big" :src="images[0]" alt="Item" />
    <div class="collection__bottom">
      <img class="collection__mini" :src="images[1]" alt="Item" />
      <img class="collection__mini" :src="images[2]" alt="Item" />
      <img class="collection__mini" :src="images[3]" alt="Item" />
    </div>
    <h4>{{ name }}</h4>
  </div>
</template>

<script>
export default {
  name: "photoCollection",
  props: {
    name: {
      type: String,
      require: false
    },
    images: {
      type: Array,
      require: false
    }
  }
}
</script>

<style scoped>

</style>