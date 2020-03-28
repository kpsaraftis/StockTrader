<template>
</template>

<script>
    export default {
        name: "Portfolio"
    };
</script>

<style>
</style>
<template>
    <div>
        <Stock v-for="stock in stocks" :key="stock.id" :stock="stock"></Stock>
    </div>
</template>

<script>
    import { mapGetters } from "vuex";
    import Stock from "./Stock.vue";
    export default {
        name: "Portfolio",
        computed: {
            ...mapGetters({
                stocks: "stockPortfolio"
            })
        },
        components: {
            Stock
        }
    };
</script>