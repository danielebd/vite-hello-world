<script>
    export default {
        data (){
            return {
                title: 'La mia prima app con Vite!',
                paragraph: 'duretta eh..',
                button: 'dai su.. cliccami'
            }
        }
    }
</script>

<template>
    <div class="container">
        <h1>{{title}}</h1>
        <p>{{ paragraph }}</p>
        <button> {{ button }}</button>
    </div>
</template>
    
<style scoped>
div {
    text-align: center;
    background-color: rgb(197, 168, 0);
    border-radius: 20px;
    padding: 40px;
}

button {
    border-radius: 10px;
    border: 0px;
    padding: 5px;
    background-color: blue;
    color: rgb(197, 168, 0);
}
</style>