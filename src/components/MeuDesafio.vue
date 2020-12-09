<template>
    <div class="meu-desafio">
        <h2>Meu Contador</h2>
        <p><strong>Contador: </strong>{{ contador }} </p>
        <button @click="subtrairUm">-</button>
        <button @click="somarUm">+</button>
    </div>
</template>

<script>
export default {
    name:'MeuDesafio',
    data(){
        return{
            contador: 0
        }
    },
    methods: {
        somarUm() {
            this.contador++;
        },
        subtrairUm() {
            this.contador--;
        }
    }
}
</script>

<style scoped>

</style>