<template>
    <ul class="catalog__list">
        <ProductItem 
        v-for="(product, idx) in products"
        :key="idx"
        :product="product"
        ></ProductItem>
    </ul>

</template>

<script>
import ProductItem from "@/components/ProductItem";

export default {
    components: {ProductItem},
    props: ['products']
}

</script>


<style scoped>
    
</style>