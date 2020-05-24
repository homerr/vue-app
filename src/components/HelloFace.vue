<template>
    <div id="facecake" class="container">
        <p class="bg-primary text-white">Muggins face</p>
        <p class="bg-warning text-white">{{ knob }}</p>
    </div>
</template>

<script>
export default {
    name: "Facecake",
    props: {
        knob: String
    }
};
</script>

<style>
    
</style>