<template>
    <div class="page-success has-text-centered">
        <div class="columns is-centered">
            <div class="column is-12 is-centered">
                <h1 class="title">Order Confirmed</h1>
                <div class="buttons is-centered">
                <router-link to="/my-account" class="button is-primary">View Your Orders</router-link>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    name: 'Success',
    mounted() {
        document.title = 'Success | BrandMerch'
    },
}
</script>