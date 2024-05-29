<!--
 * @Author: 孙林 1164700321@qq.com
 * @Date: 2024-05-07 14:51:36
 * @LastEditors: 孙林
 * @LastEditTime: 2024-05-07 15:00:29
 * @Description: 
-->
<template>
    <div class="page_wrapper">
        <h1>test</h1>
        <p>{{ msg }}</p>
    </div>
</template>
<script>
export default {
    name: 'test',
    data() {
        return {
            msg: 'Welcome to Your Vue.js App'
        }
    }
}
</script>
<style scoped>
    .page_wrapper{
        text-align: center;
    }
</style>