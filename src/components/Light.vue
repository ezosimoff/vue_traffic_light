<template>
  <div :class="color"></div>
</template>

<script>
export default {
  name: "Light",
  props: {
    color: {
      type: String,
    },
    time: {
      type: Number,
    },
  },
};
</script>

<style scoped>
.red {
  opacity: 0.2;
  background: red;
  background-image: radial-gradient(brown, transparent);
  background-size: 5px 5px;
  width: 74px;
  height: 74px;
  border-radius: 50%;
  position: absolute;
  top: 303px;
  left: 604px;
  -webkit-animation: 13s red infinite;
  animation: 13s red infinite;
  border: dotted 2px darkred;
  box-shadow: 0 0 20px #111 inset, 0 0 10px red;
}

.yellow {
  opacity: 0.2;
  background: yellow;
  background-image: radial-gradient(orange, transparent);
  background-size: 5px 5px;
  width: 74px;
  height: 74px;
  border-radius: 50%;
  border: dotted 2px #c1c100;
  position: absolute;
  top: 401px;
  left: 602px;
  animation: 13s yellow infinite;
  box-shadow: 0 0 20px #111 inset, 0 0 10px yellow;
}

.green {
  opacity: 0.2;
  background: green;
  background-image: radial-gradient(lime, transparent);
  background-size: 5px 5px;
  width: 74px;
  height: 74px;
  border-radius: 50%;
  border: dotted 2px #007400;
  position: absolute;
  top: 499px;
  left: 598px;
  box-shadow: 0 0 20px #111 inset, 0 0 10px lime;
  -webkit-animation: 13s green infinite;
  animation: 13s green infinite;
}
</style>