<template>
  <div class="about">
    <h1>This is an about page</h1>
    <h1>This will teach you why you call me father</h1>
    <p>
      <HelloPapa msg="Hello Papa" />
    </p>
  </div>
</template>
<script>
import HelloPapa from "@/components/HelloPapa.vue";
export default {
  name: "About",
  components: {
    HelloPapa,
  },
};
</script>

<style scoped>
p {
  color: #42b983;
}
h1 {
  color: 42b983;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
 {
  color: #06fad2;
}
</style>


