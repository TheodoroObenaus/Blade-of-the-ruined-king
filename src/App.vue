<script setup>
const produtos = [
    {
        id: 1,
        nome: 'Camiseta',
        preco: 49.90
    },
    {
        id: 2,
        nome: 'Calça',
        preco: 99.90
    },
    {
        id: 3,
        nome: 'Meia',
        preco: 9.90
    },
    {
        id: 4,
        nome: 'Sapato',
        preco: 199.90
    },
    {
        id: 5,
        nome: 'Boné',
        preco: 29.90
    },
    {
        id: 6,
        nome: 'Óculos',
        preco: 99.90
    },
    {
        id: 7,
        nome: 'Relógio',
        preco: 299.90
    },
    {
        id: 8,
        nome: 'Bermuda',
        preco: 79.90
    },
    {
        id: 9,
        nome: 'Cueca',
        preco: 19.90
    },
    {
        id: 10,
        nome: 'Meia',
        preco: 9.90
    }
]
</script>

<template>
 
<div class="barracima">
    <img src="carrinho.png" alt="carinho.png" width="60" class="carinho" >
    <h1>Compras Gamers</h1>
    <button class="dog"><img src="carinhpcachorro.png" alt="cachorro" width="60"></button>
</div>

</template>

<style scoped>
.dog {
    border: solid white 1px;
    background-color: white;
}
.carinho {
    border-radius: 100px;
}
.barracima {
    background-color: blue;
    color: white;
    margin-bottom: 1000px;
}
</style>
