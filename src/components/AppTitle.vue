<script>
export default {
    data() {
        return { 
            title : 'La mia prima app con Vite' 
        };
    },
};
</script>

<template>
    <div>
        <p>
            {{ title }}
        </p>
    </div>
</template>

<style scoped>
p{
    text-align: center;
    font-size: 2rem;
    color: lightblue;
    background-color: black;
}
</style>
