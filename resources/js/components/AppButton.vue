<template>
    <!-- <button>{{ text }}</button> -->

    <button><slot></slot></button>
    
</template>

<script>
    export default {
        // props: ["text"]
    };
</script>

<style lang="scss" scoped>
     button{
         background-color: #32b8ea;
         border-radius: 5px;
         color: #fff;
         text-align: center;
         border: none;
         padding: 10px 20px;
     }
</style>