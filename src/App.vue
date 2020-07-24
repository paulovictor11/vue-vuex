<template>
    <div id="app">
        <product-list-one></product-list-one>
        <product-list-two></product-list-two>
    </div>
</template>

<script>
    import ProductListOne from './components/ProductListOne';
    import ProductListTwo from './components/ProductListTwo';

    export default {
        name: 'App',
        data () {
            return {
                
            }
        },
        components: {
            ProductListOne, ProductListTwo
        }
    }
</script>

<style>

</style>
