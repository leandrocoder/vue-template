<template>
    <div class="page">
        <page-header />
        <h1>About</h1>
    </div>   
</template>

<script>
    import PageHeader from '../components/Header.vue';
    export default {
        components: {
            PageHeader
        }
    }
</script>

<style lang="scss" scoped>
    .page {
        position:absolute;
        padding: 20px;
        top:0px;
        left:0px;
        width: 100vw;
        height: 100vh;
        background-color: blue;
        color:white;
    }
</style>