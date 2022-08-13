<template>
  <div id="school">
    <h3>公司:{{ name }}</h3>
    <h3>地址:{{ add }}</h3>
  </div>
</template>

<script>
export default {
  name: "School",
  data() {
    return {
      name: "助手软件",
      add: "三好街",
    };
  },
};
</script>

<style>
#school {
  background: orange;
}
</style>

