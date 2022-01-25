<template>
  <el-form ref="formRef" :model="form" label-width="120px"> </el-form>
</template>

<script lang="ts" setup>
import { reactive } from "vue";
interface UserInfo {
  name: string;
  stuNum: number;
  sfz: number;
  email: string;
}
const form = reactive<UserInfo>();
console.log(form);

// const onSubmit = () => {
//   console.log("submit!");
// };
</script>
