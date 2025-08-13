<template>
    <div>
        <h1>Primeiro Componente</h1>
    </div>
</template>

<style scoped>
div {
    background-color: grey;
    padding: 20px;
    margin: 30px;
    border-radius: 5px;
    text-align: center;
}

div:hover {
    background-color: rgb(105, 104, 104);
    transition: all 0.3s ease;
    transform: scale(1.0);
    cursor: pointer;
    box-shadow: 0 4px 8px rgba(0, 0,0, 0.3)
}

h1 {
    color: white;
    margin-bottom: 10px;
}
</style>