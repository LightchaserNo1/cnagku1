<template>
<div class="box">
    <div class="con">
        <h3>登录</h3>
        <div class="inp"><input type="text"></div>
        <div class="inp"><input type="password"></div>
        <div class="inp"><button>登录</button></div>
    </div>
 </div>
</template>
<script>
export default {
 components: {},
 data() {
 return {};
},
 methods: {},
 mounted() {},
};
</script>
<style scoped>
    .box{
        width:100vw;
        height: 100vh;
        background:linear-gradient(to right,#563443,#303D60);
    }
    .con{
        width: 400px;
        height: 300px;
        background-color:white;
        position: relative;
        border-radius:10px ;
        left:50%;
        top:50%;
        transform: translate(-50%,-50%);
    }
    h3{
        width: 100%;
        text-align: center;
    }
    .inp{
        width: 300px;
        height: 30px;
        margin:30px auto;
       
        text-align: center;
    }
    input{
        width:94%;
        height: 100%;
         border:1px solid black;
    }
    button{
        width: 96%;
        height: 30px;
        text-align: center;
        color:white;
        background-color:#02B4FF;
        border-radius:5px;
    }
</style>
