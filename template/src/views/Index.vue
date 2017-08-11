<template>
    <div class="page-index">
        <img src="../assets/images/logo.png">
        <h1>{{ title }}</h1>
        <p>{{text}}</p>
    </div>
</template>

<script>
    export default {
        name: 'index',
        data() {
            return {
                title: 'Welcome to use jmv to build your Vue.js App',
                text: "It's a webpack&vue&vuex&vue-router project.",
            }
        }
    }
</script>

<style rel="stylesheet/scss" lang="scss">
    h1 {
        font-size: 18px;
    }
    .page-index {
        text-align: center;
    }
</style>