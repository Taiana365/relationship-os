<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Relationship OS</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Segoe UI, sans-serif;
}

body{
    background:#0d1117;
    color:#e6edf3;
}

.login{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
}

.login-box{
    background:#161b22;
    padding:40px;
    border-radius:15px;
    width:350px;
    text-align:center;
    border:1px solid #30363d;
}

.login-box h1{
    color:#58a6ff;
    margin-bottom:15px;
}

.login-box input{
    width:100%;
    padding:12px;
    margin-top:15px;
    border:none;
    border-radius:8px;
}

.login-box button{
    margin-top:15px;
    width:100%;
    padding:12px;
    border:none;
    border-radius:8px;
    background:#238636;
    color:white;
    cursor:pointer;
}

#conteudo{
    display:none;
}

header{
    padding:60px 20px;
    text-align:center;
}

header h1{
    color:#58a6ff;
    font-size:3rem;
}

header p{
    margin-top:10px;
    color:#8b949e;
}

section{
    max-width:1000px;
    margin:auto;
    padding:40px 20px;
}

.card{
    background:#161b22;
    border:1px solid #30363d;
    border-radius:15px;
    padding:20px;
    margin-top:15px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:15px;
}

.trofeu{
    background:#161b22;
    border:1px solid #30363d;
    border-radius:15px;
    padding:20px;
}

.trofeu:hover{
    transform:translateY(-5px);
    transition:.3s;
}

h2{
    margin-bottom:20px;
    color:#58a6ff;
}

.metricas{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:15px;
}

.metrica{
    background:#161b22;
    padding:20px;
    border-radius:15px;
    text-align:center;
    border:1px solid #30363d;
}

.final{
    text-align:center;
    padding:80px 20px;
}

.botao{
    margin-top:25px;
    padding:15px 30px;
    border:none;
    border-radius:10px;
    background:#238636;
    color:white;
    cursor:pointer;
    font-size:18px;
}

#resultado{
    display:none;
    margin-top:30px;
    font-size:1.2rem;
}

footer{
    text-align:center;
    padding:40px;
    color:#8b949e;
}
</style>

</head>
<body>

<div class="login" id="login">

<div class="login-box">

<h1>Relationship OS</h1>

<p>Sistema iniciado em 12/06/2025</p>

<input type="password" id="senha" placeholder="Digite a senha">

<button onclick="entrar()">Entrar</button>

<p id="erro" style="color:red;margin-top:10px;"></p>

</div>

</div>

<div id="conteudo">

<header>
<h1>Relationship OS</h1>
<p>Renato & Taiana</p>
<p>Sistema em produção há 365 dias ❤️</p>
</header>

<section>

<h2>📊 Dashboard</h2>

<div class="metricas">

<div class="metrica">
<h3>Status</h3>
<p>Estável ❤️</p>
</div>

<div class="metrica">
<h3>Disponibilidade</h3>
<p>100%</p>
</div>

<div class="metrica">
<h3>Compatibilidade</h3>
<p>100%</p>
</div>

<div class="metrica">
<h3>Versão Atual</h3>
<p>1.0</p>
</div>

</div>

</section>

<section>

<h2>🏆 Conquistas Desbloqueadas</h2>

<div class="grid">

<div class="trofeu">
<h3>🏆 Primeiro Encontro</h3>
<p>Conquista desbloqueada.</p>
</div>

<div class="trofeu">
<h3>🏆 Primeiro Beijo</h3>
<p>Atualização crítica do sistema.</p>
</div>

<div class="trofeu">
<h3>🏆 Posso te buscar em casa?</h3>
<p>Nível de confiança aumentado.</p>
</div>

<div class="trofeu">
<h3>🏆 Integração Completa</h3>
<p>Sistemas compatíveis.</p>
</div>

<div class="trofeu">
<h3>🏆 Família</h3>
<p>Módulo aprovado.</p>
</div>

<div class="trofeu">
<h3>🏆 Viagem Internacional</h3>
<p>Feature planejada.</p>
</div>

</div>

</section>

<section>

<h2>🐞 Bugs Conhecidos</h2>

<div class="card">
Bug #001 — Saudade excessiva quando distante.
</div>

<div class="card">
Bug #002 — Vontade de ficar mais cinco minutos.
</div>

<div class="card">
Bug #003 — Ficar olhando fotos antigas.
</div>

</section>

<section>

<h2>📜 Logs do Sistema</h2>

<div class="card">
12/06/2025 — Deploy inicial realizado.
</div>

<div class="card">
Primeira atualização concluída com sucesso.
</div>

<div class="card">
Sistema apresentou crescimento acima do esperado.
</div>

<div class="card">
Planejamento da expansão internacional iniciado.
</div>

</section>

<section>

<h2>🚀 Roadmap v2.0</h2>

<div class="card">
✈️ Leste Europeu
<br><br>
❤️ Mais memórias
<br><br>
📸 Novas aventuras
<br><br>
🍣 Mais jantares
<br><br>
🏡 Atualizações de longo prazo
</div>

</section>

<section class="final">

<h2>Relatório de Desempenho</h2>

<div class="card">
Cargo: Namorada<br><br>
Tempo de experiência: 365 dias<br><br>
Avaliação: Excelente<br><br>
Compatibilidade: 100%
</div>

<button class="botao" onclick="avaliar()">
Executar Avaliação
</button>

<div id="resultado">

<h2>Aprovada com distinção ❤️</h2>

<p>
Você se tornou uma das melhores partes da minha vida.
</p>

<br><br>

<h1>Vou ser contratada para a Versão 2.0?</h1>

<br>

<button class="botao" onclick="alert('Contrato aceito ❤️')">
SIM
</button>

<button class="botao" onclick="alert('COM CERTEZA ❤️')">
COM CERTEZA
</button>

</div>

</section>

<footer>
Relationship OS v1.0
</footer>

</div>

<script>

function entrar(){

const senha =
document.getElementById("senha").value;

if(senha==="12062025"){

document.getElementById("login").style.display="none";
document.getElementById("conteudo").style.display="block";

}else{

document.getElementById("erro").innerText =
"Senha incorreta.";

}

}

function avaliar(){

document.getElementById("resultado").style.display="block";

window.scrollTo({
top:document.body.scrollHeight,
behavior:'smooth'
});

}

</script>

</body>
</html>
