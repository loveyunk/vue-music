<template>
    <div class="slider">
        <div class="slider-group">
            <slot></slot>
        </div>
        <div class="dots">

        </div>
    </div>
</template>

<script>
    export default {
        props: {
            loop: {
                type: Boolean,
                default: true
            },
            autoPlay: {
                type: Boolean,
                default: true
            },
            interval: {
                type: Number,
                default: 4000
            }
        }
    };
</script>

<style>

</style>
