<template>
    <div class="hello">
        <h1>{{ msg }}</h1>
        <van-button class="btn" type="primary">主要按钮</van-button>
        <van-button class="btn" type="info">信息按钮</van-button>
        <van-button class="btn" type="default">默认按钮</van-button>
        <van-button class="btn" type="warning">警告按钮</van-button>
        <van-button class="btn" type="danger">危险按钮</van-button>
    </div>
</template>

<script>
    export default {
        name: 'HelloWorld',
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .btn {
        margin-left: 20px;
    }
</style>
