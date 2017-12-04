<template>
  <div class="footer">
    <span>版权所有：&nbsp;&copy;&nbsp;<a :href="siteInfo.url">{{siteInfo.name}}</a></span>
  </div>
</template>

<script>
export default {
  name: "vFooter",
  data() {
    return {};
  },
  props: ["siteInfo"]
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
  width: 100%;
  padding: 10px 0;
  background-color: #242424;
  color: #f91;
  font-size: 12px;
  font-weight: normal;
}
a {
  color: #f91;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}
</style>
