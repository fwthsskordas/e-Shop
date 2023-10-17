<template>
    <div>
        <h2>About</h2>
        <p> Lorem 2 </p>
         <p>api response:</p>
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