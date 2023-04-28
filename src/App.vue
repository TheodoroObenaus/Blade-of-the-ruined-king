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
<div class="barra">
    
    <div class="logo">
        <img src="carrinho.png" alt="carinho.png" width="100px" class="carinho" >
    </div>

    <div class="barracima">
        <h1>Compras Gamers</h1>
    </div>

    <div class="botaocar">
        <button class="dog"><img src="carinhpcachorro.png" alt="cachorro" width="100px"></button>
    </div>

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

.barra{
    display: grid;
    grid-template-columns: 100px 500px 100px;
    grid-template-rows: auto;
    justify-content: space-between;
    border-bottom: 10px solid black;
}

.barracima {
    color: black;
    text-align: center;
}
.botaocar {
    color: white;
}

.logo {
    color: white;
}
</style>
