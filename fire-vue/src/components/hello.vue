<template>
    <p class="message">メッセージ：{{ msg }}</p>
</template>

<script>
    export default {
        name: "hello",
        data() {
            return { msg: 'こんにちは'}
        }
    }
</script>

<style scoped>
    .message { color: #42b983; }
</style>