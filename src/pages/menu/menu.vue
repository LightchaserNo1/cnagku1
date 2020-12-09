<template>
<div>
    <el-button type="primary">添加</el-button>
    <!-- 添加 -->
    <v-add></v-add>
    <!-- 列表 -->
    <v-list></v-list>
 </div>
</template>
<script>
import vAdd from "./components/add"
import vList from "./components/list"
export default {
 components: {
     vAdd,
     vList
 },
 data() {
 return {
    
 };
},
 methods: {

 },
 mounted() {},
};
</script>
<style>
</style>