<template>
    <div class="welcome">
        <div style="font-size: 50px">404 not found</div>
    </div>
</template>
<script>
    export default {
        name: "error",
        data() {
            return {

            };
        },
        components : {

        }
    };
</script>
<style scoped>
    .welcome {
        display : flex;
        align-items: center;     /* 垂直居中 */
        justify-content:center; /*水平居中*/
        width:100%;
        height: 100%;
        background-color: #c1c1c1;
    }
</style>