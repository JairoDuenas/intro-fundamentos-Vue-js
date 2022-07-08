<template>
  <div>
    <p>Lorem ipsum dolor sit</p>
    <div>{{ text }}</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: "Hola!",
    };
  },
};
</script>

<style>
p {
  color: brown;
}
</style>
