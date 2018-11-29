<template>
    <div class="product-component">
        {{ message }}
    </div>
</template>

<script>
    export default {
        data() {
            return {
                message: 'Hello World!'
            }
        }
    }
</script>

<style lang="scss" scoped>
    .product-component {
        color: red;
    }
</style>
