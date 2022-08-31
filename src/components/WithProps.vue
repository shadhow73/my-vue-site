<script>
    export default{
        props : {
            text : {
                type: String
            }
        },
        methods:{
            loadPage(page){
                this.$parent.loadPage(page);
            }
        }
    }

</script>

<template>

<h2 class="w3-center">{{text}}</h2>
            
</template>