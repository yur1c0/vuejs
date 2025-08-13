<template>
    <div class="componente">
        <h1>Componente com Dados Reativos</h1>
        <p>Nome: {{ nome }} | Idade: {{ idade }}</p>
        <button v-on:click="fazerAniversario()">Fazer Aniversario</button>
        <button @click="mudarNome">Mudar nome</button>
    </div>
</template>

<script setup>
import { ref } from 'vue';

    const nome = ref("Ana");
    const idade = ref(17);

    function fazerAniversario(){
        idade.value += 1;
    }

    function mudarNome(){
        nome.value = "Pedro";
    }
</script>