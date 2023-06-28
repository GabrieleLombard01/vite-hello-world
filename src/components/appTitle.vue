<script>
export default {
    data() {
        return {
            phrase: 'La mia prima app con Vite!'
        }
    }
}
</script>

<template>
    <!--TITLE:-->
    <h1>{{ phrase }}</h1>
</template>

<style scoped>
h1 {
    color: blue;
    text-shadow: 2px 2px red;
    text-align: center;
}
</style>
