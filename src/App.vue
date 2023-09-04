<template>
  <el-input placeholder="Please input" v-model="input"></el-input>
  {{ input }}
</template>


<script>
import { ref } from "vue";
export default {
  setup() {
    const input = ref("");
    return {
      input,
    };
  },
};
</script>
