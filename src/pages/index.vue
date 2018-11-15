<!--此处为1级页面-->
<template>
    <div class="index">
        <main-head title="登录"></main-head>
        <div class="con">首页内容</div>
    </div>
</template>

<script>
    import MainHead from "../components/Header";
    export default {
        name: 'index',
        components: {MainHead},
        data () {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
    .index {
        width: 750px;
        background: red;
    }
    .con {
        height: 50px;
        background: url("../assets/common/title_back.png") no-repeat;
    }
</style>
