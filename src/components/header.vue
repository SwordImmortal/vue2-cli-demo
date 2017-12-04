<template>
  <div class="header">
    <h1>{{siteInfo.title}}</h1>
    <h5>{{siteInfo.desc}}</h5>
  </div>
</template>

<script>
export default {
  name: "vHeader",
  data() {
    return {};
  },
  props: ["siteInfo"]
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  width: 100%;
  padding: 20px 0;
  background-color: #f91;
  color: #fff;
}
h1 {
  margin: 10px auto;
}
h5 {
  font-weight: normal;
}
</style>
