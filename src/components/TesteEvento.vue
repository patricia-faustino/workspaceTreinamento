<template>
    <div class="teste-evento">
        <h2>TesteEvento</h2>
        <p @click="deixarMaiuscula">{{ mensagem }}</p>
    </div>
</template>

<script>
export default {
    name: 'TesteEvento',
    data(){
        return{
           mensagem: 'o rato roeu a roupa do rei de Roma' 
        }
    },
    methods:{
        deixarMaiuscula(){
            this.mensagem = this.mensagem.toUpperCase();
        }
    }
}
</script>

<style scoped>

</style>