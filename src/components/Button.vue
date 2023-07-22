<template>
    <button @click="onClick('click-btn')" class="btn" :style="{background: color}">{{ text }}</button>
</template>

<script>
    export default {
        name: "Button",
        props: {
            text: String,
            color: String,
        },

        methods: {
            onClick() {
                console.log('click')
            }
        }
    }
</script>

<style>

</style>