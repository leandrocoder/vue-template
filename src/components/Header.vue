<template>
    <div class='pageheader'>
        <div v-for="(item, index) in pages">
            <a :href="item.page">{{item.label}}</a>
        </div>
    </div>
</template>

<script>
    export default {
       data: () => ({
           pages: [
               {label:"Home Page", page:"#/"},
               {label:"About Us", page:"#/about"}
           ]
       })
    }
</script>

<style lang="scss" scoped>

    .pageheader {
        position:relative;
        width:100%;
        color:black;
        padding: 20px;
        background-color: white;
        margin-bottom: 20px;
        display: flex;

        a {
            margin-right: 20px;
        }
    }
   
</style>