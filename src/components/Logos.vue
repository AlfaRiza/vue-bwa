<template>
  <div class="logos-wrapper">
    <h2>Find the Best Logos</h2>
    <div class="item-logos">
      <img src alt />
    </div>
    <div class="item-logos">
      <img src alt />
    </div>
    <div class="item-logos">
      <img src alt />
    </div>
    <div class="item-logos">
      <img src alt />
    </div>
  </div>
</template>

<script>
export default {
  name: "Logos"
};
</script>

<style scoped>
.logos-wrapper {
  width: 80%;
  background: green;
  margin: auto;
  overflow: hidden;
}

.item-logos {
  float: left;
  width: 150px;
  height: 150px;
  background: blue;
  margin: 0 10px;
  /* margin: auto; */
}
</style>