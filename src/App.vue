<template>
  <div class="container">
    <img src="./assets/traffic-light.jpg" alt="" class="bg-image" />

  </div>
</template>

<script>
export default {
  data() {
    return {
      pages: [
        { id: 1, color: "red", path: "/red", time: 10 },
        { id: 2, color: "yellow", path: "/yellow", time: 3 },
        { id: 3, color: "green", path: "/green", time: 15 },
      ],
    };
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container {
  position: relative;
  width: 100%;
  height: 100vh;
  overflow: hidden;
}
</style>