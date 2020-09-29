<template>
  <div class="daddy">
    <h1>Daddy is Coming</h1>
    <p>
      <HelloDaddy msg="お帰り お父さん" />
    </p>
  </div>
</template>

<script>
import HelloDaddy from "@/components/HelloDaddy.vue";
export default {
  name: "Daddy",
  components: {
    HelloDaddy,
  },
};
</script>

<style scoped>
p {
  color: #42b983;
}
</style>