<template>
    <div>
        <H1>Componente com dados</H1>
        <p>Nome: {{ nome }} </p>
        <p>Idade: {{ idade }}</p>
        <p>Altura: {{ altura }}</p>
    </div>
</template>
    
<style scoped>
div{
    text-align: center;
    margin: 30px;
    border: 2px solid rgb(0, 0, 0);
    background-color: grey;
    border-radius: 15px;
    padding: 10px;
    font-family: 'Courier New', Courier, monospace;
}

p{
    font-size: 30px;
    font-family: 'Courier New', Courier, monospace;
}

</style>
<script setup>
const nome = "Pedro";
const idade = 18;
const altura = 2.3;
</script>

<!--
<script>
//option API
//export default{
//    data: function(){
//        return{
//            nomeProduto: "Caderno",
//            codigoProduto: "#321"
//        }
//    }
//}

// Composition API
//export default{
//    setup: function(){
//        const nomeProduto = "Lapis"
//        const codigoProduto = "#454"
//        return {nomeProduto, codigoProduto}
//    }
//}
// </script> -->