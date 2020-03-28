<template>
    <div>
      <app-Stock v-for="stock in stocks"></app-Stock>  
    </div>
</template>

<script>
    import Stock from './Stock.vue'
    export default {
        data() {
            return {

            stocks: [
                { id: 1, name: "BMW", price: 110 },
                { id: 2, name: "Google", price: 20 },
                { id: 3, name: "Apple", price: 250 },
                { id: 4, name: "Twitter", price: 8 }
            ]
            };
        },
        components: {
            appStock: Stock
        }

    }
</script>

<style>
</style>
