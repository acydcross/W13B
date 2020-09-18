<template>
    <div @click="makeRed" :class="{ bodygrid: isGrid }">
        <h3 v-for="name in names" v-bind:key="name">{{ name }}</h3>
    </div> 
</template>

<script>

export default {
    
}
</script>

<style scoped>
.bodygrid {
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-columns: repeat(4, 1fr);
    }

</style>