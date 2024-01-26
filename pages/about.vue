<template>
    <div>
        <h2>ABOUT</h2>
        <p class="font-mono"> Go to products to see the magic. </p>
        <div>
            {{ data }}
        </div>
    </div>
</template>

<script setup>
     const { data } = await useFetch('/api/snap')
</script>

<style scoped>
h2{
    margin-bottom: 20px;
    font-size: 36px;
}

p{
    margin: 20px 0;
}
</style>