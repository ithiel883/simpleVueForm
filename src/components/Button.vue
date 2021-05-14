<template>
    <button @click="onClick()">Submit</button>
</template>

<script>
export default {
    name: 'Button',
    props: {
         
    },
    methoods: {
        onClick() {
            console.log("Submitted")
        }
    }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital@1&display=swap');

button {
    font-family: 'Montserrat', sans-serif;
}
</style>