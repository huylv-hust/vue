<template>
    <div class="product-component">
        <div>{{ message }}</div>
        <div>
            <button @click="printText">Click Me</button>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                message: 'Hello World ^^'
            }
        },
        methods: {
            printText() {
                //alert("Hello every body! Love all ^^")
                this.message = "You are my everything ^^";
            }
        }
    }
</script>

<style lang="scss" scoped>
    .product-component {
        color: red;
    }
</style>
