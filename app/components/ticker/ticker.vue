<template>
    <label for="ticker">ticker</label>
    <select name="ticker">
        <option v-for="option in options">{{option.tickerName}}</option>
    </select>
</template>

<script>
    export default {
        name: "ticker"
    }
</script>

<style scoped>

</style>