<template>
    <!--<h1>welcome Vue</h1>
    <h2 @click="change">{{msg}}</h2>
    <my-menu></my-menu>-->
    <div id="app">
        <h3>vue-loader+ vue-router</h3>
        <div>
            <a v-link="{path:'/home'}">主页</a>
            <a v-link="{path:'/news'}">新闻</a>
        </div>
        <router-view></router-view>
    </div>
</template>
<script>
    /*import Menu from './components/Menu.vue'
    export default{
        data(){
            return {
                msg:'welcome vue'
            }
        },
        methods:{
            change(){
                this.msg='wahaha'
            }
        },
        components:{
            'my-menu':Menu
        }
    }*/
</script>
<style>
    body{
        background:#ccc;
    }
    .v-link-active{
        font-size:20px;
        color:#f60;
    }
</style>