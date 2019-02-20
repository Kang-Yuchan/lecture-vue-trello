<template>
    <div>
        Board
        <div>bid: {{bid}}</div>
    </div>
</template>

<script>
export default {
    created() {
        this.bid=this.$route.params.bid
    }
}
</script>

<style>

</style>
