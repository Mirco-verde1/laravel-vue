<template>
    <div>

       <h1>{{catalogue.title}}</h1> <span>Price :{{catalogue.price}}</span>
    </div>
</template>


<script>

export default {

  name: 'BaseComponent',

    props: {

        catalogue:Object
    },

}
</script>



<style scoped>

</style>
