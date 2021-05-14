<template>
<div>
    <ul>
        <li>Name: <input type="text" name="" id=""></li>
        <li>Age: <input type="number" name="" id=""></li>
        <li>Height: <input type="Number" name="" id="" placeholder="cm"></li>
        <li>School: <input type="text" name="" id=""></li>

    </ul>

</div>

</template>

<script>
export default {
    name: 'Form',
    components: {
    },
    props: {

    }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,200&display=swap');

div {
    font-family: 'Montserrat', sans-serif;
}
ul {
    display: grid;
    list-style-type: none;
}
input {
        background: rgba(115, 128, 0, 0.563);

    margin: 4px;
    padding: 3px;
    border-radius: 9px;
}
</style>