<template>
  <div class="school">
    <h2>1: {{ name }}</h2>
    <h2>2: {{ address }}</h2>
  </div>
</template>

<script>
export default {
  name: "SchoolInfo",
  data() {
    return {
      name: "scName",
      address: "scAdd",
    };
  },
};
</script>

<style>
.school {
  background-color: beige;
}
</style>