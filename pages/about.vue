<template>
    <div>
        <h2>About</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quis nulla minus architecto optio porro illum
            vitae, repudiandae dolores ratione. Aperiam tenetur corporis deserunt excepturi enim molestiae perferendis
            optio nisi ea.</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Illum, minima, quia esse consequatur molestiae eos
            dolore repellat tempora unde exercitationem provident! Similique ratione ut labore vel sint dolor minus
            assumenda?</p>
        <div>{{ data }}</div>
    </div>
</template>

<script setup>
const { data } = await useFetch('/api/currency/GBP')
</script>

<style scoped>
h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

p {
    margin: 20px 0;
}
</style>