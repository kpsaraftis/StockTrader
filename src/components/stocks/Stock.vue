<template>
    <div class="panel panel-success">
        <div class="panel-heading">
            <h3 class="panel-title">
                NAME
                <small>(price: (PRICE))</small>
            </h3>
        </div>
        <div class="panel-body">
            <div class="pull-left">
                <input type="number" class="form-control" placeholder="Quantity" />
            </div>
            <div class="pull-right">
                <button class="btn btn-success">Buy</button>
            </div>
        </div>
    </div>
</template>

<script>

    export default {
        name: "Stock",
    }
</script>

<style>
</style>
