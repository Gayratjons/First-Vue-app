<template>
    <div class="div">
        <button :class="variable" v-on:click="handleClick">
            Click me
        </button>
    </div>
    <h1 :id="id">Hello</h1>
</template>

<script>
export default {
    name: 'New',
    data() {
        return {
            variable: 'Umar',
            id: 'text'
        }
    },
    methods: {
        handleClick() {
            const txt = document.getElementById("text");
            txt.style.color = 'red'
        }
    },
}
</script>

<style>
.div {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}

/* .div {
    width: 100px;
    height: 100px; */
/* } */
</style>
