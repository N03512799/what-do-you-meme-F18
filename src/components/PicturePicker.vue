<template>
    <div>
        <a v-for="p in pictures" :key="p.id">
            
        </a>
    </div>
</template>
<script>
export default {
    data: function () {

    },
    props: {
        pictures: Array
    }
}
</script>
<style lang="scss">

</style>