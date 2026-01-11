<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Loja de E-books</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f2f2f2;
}
header {
    background: #2ecc71;
    color: white;
    text-align: center;
    padding: 20px;
}
.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
}
.card {
    background: white;
    border-radius: 8px;
    padding: 20px;
    text-align: center;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
.card h2 {
    font-size: 20px;
}
.price {
    color: #27ae60;
    font-size: 18px;
    margin: 10px 0;
}
button {
    background: #2ecc71;
    color: white;
    border: none;
    padding: 12px;
    width: 100%;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
}
button:hover {
    background: #27ae60;
}
footer {
    text-align: center;
    padding: 15px;
    background: #ddd;
    font-size: 14px;
}
</style>
</head>

<body>

<header>
    <h1>📚 Loja de E-books Digitais</h1>
    <p>Conhecimento prático para mudar sua vida</p>
</header>

<div class="container">

    <div class="card">
        <h2>E-book Emagrecimento</h2>
        <p>Dicas + Receitas saudáveis</p>
        <div class="price">R$ 19,90</div>
        <button onclick="alert('Coloque aqui o link do pagamento')">Comprar</button>
    </div>

    <div class="card">
        <h2>E-book Fitness</h2>
        <p>Treinos simples em casa</p>
        <div class="price">R$ 14,90</div>
        <button onclick="alert('Coloque aqui o link do pagamento')">Comprar</button>
    </div>

    <div class="card">
        <h2>E-book Alimentação</h2>
        <p>Cardápios fáceis e baratos</p>
        <div class="price">R$ 17,90</div>
        <button onclick="alert('Coloque aqui o link do pagamento')">Comprar</button>
    </div>

    <div class="card">
        <h2>E-book Mentalidade</h2>
        <p>Foco, disciplina e motivação</p>
        <div class="price">R$ 12,90</div>
        <button onclick="alert('Coloque aqui o link do pagamento')">Comprar</button>
    </div>

</div>

<footer>
    <p>© 2026 - Loja de E-books | Todos os direitos reservados</p>
</footer>

</body>
</html>
