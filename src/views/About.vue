<template>
  <div id="about">
    <h1 v-text="msg"></h1>
    <button @click="showDOM">点我输出上方的DOM元素</button>
    <School />
    <hr />
    <Student />
  </div>
</template>

<script>
import School from "@/components/School";
import Student from "@/components/Student";

export default {
  name: "About",
  data() {
    return {
      msg: "欢迎学习Vue!",
    };
  },
  components: {
    School,
    Student,
  },
  methods: {
    showDOM() {
      console.log("@@");
    },
  },
};
</script>

<style>
#about {
  text-align: left;
}
</style>
