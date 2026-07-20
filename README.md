# surpresa<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Uma Pergunta Especial</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:linear-gradient(135deg,#ff9ec4,#ffd6e8);
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.caixa{
    background:white;
    padding:40px;
    border-radius:20px;
    text-align:center;
    box-shadow:0 10px 30px rgba(0,0,0,.2);
    max-width:400px;
}

h1{
    color:#e91e63;
    margin-bottom: 10px;
}

.emoji-inicio {
    font-size: 45px;
    margin-bottom: 20px;
}

button{
    padding:12px 28px;
    margin:10px;
    font-size:18px;
    border:none;
    border-radius:10px;
    cursor:pointer;
    transition:.3s;
}

#sim{
    background:#4CAF50;
    color:white;
}

#nao{
    background:#f44336;
    color:white;
}

#mensagem{
    display:none;
    margin-top:20px;
    animation:aparecer 1s;
}

#mensagem h2 {
    color:#e91e63;
    font-size: 22px;
}

#mensagem p {
    font-size: 14px;
    color: #555;
    line-height: 1.5;
}

@keyframes aparecer{
    from{opacity:0;transform:scale(.8);}
    to{opacity:1;transform:scale(1);}
}
</style>
</head>

<body>

<div class="caixa">
    <div id="conteudo-principal">
        <h1>Quer namorar comigo?</h1>
        <div class="emoji-inicio">🪻</div>
        <button id="sim" onclick="aceitou()">Sim</button>
        <button id="nao" onclick="sumir()">Não</button>
    </div>

    <div id="mensagem">
        <h2>Eu sabia que você diria sim!</h2>
        <p>
            Você faz os meus dias mais felizes e transforma os momentos simples em lembranças especiais.
            Prometo cuidar de você, respeitar você e estar ao seu lado nos dias bons e nos difíceis.
            Que esse seja apenas o começo de uma linda história. Eu te amo!
        </p>
    </div>
</div>

<script>
function sumir(){
    document.getElementById("nao").style.display="none";
}

function aceitou():void {
    document.getElementById("conteudo-principal").style.display="none";
    document.getElementById("mensagem").style.display="block";
}
</script>

</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Uma Pergunta Especial</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:linear-gradient(135deg,#ff9ec4,#ffd6e8);
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.caixa{
    background:white;
    padding:40px;
    border-radius:20px;
    text-align:center;
    box-shadow:0 10px 30px rgba(0,0,0,.2);
    max-width:400px;
}

h1{
    color:#e91e63;
    margin-bottom: 10px;
}

.emoji-inicio {
    font-size: 45px;
    margin-bottom: 20px;
}

button{
    padding:12px 28px;
    margin:10px;
    font-size:18px;
    border:none;
    border-radius:10px;
    cursor:pointer;
    transition:.3s;
}

#sim{
    background:#4CAF50;
    color:white;
}

#nao{
    background:#f44336;
    color:white;
}

#mensagem{
    display:none;
    margin-top:20px;
    animation:aparecer 1s;
}

#mensagem h2 {
    color:#e91e63;
    font-size: 22px;
}

#mensagem p {
    font-size: 14px;
    color: #555;
    line-height: 1.5;
}

@keyframes aparecer{
    from{opacity:0;transform:scale(.8);}
    to{opacity:1;transform:scale(1);}
}
</style>
</head>

<body>

<div class="caixa">
    <div id="conteudo-principal">
        <h1>Quer namorar comigo?</h1>
        <div class="emoji-inicio">🪻</div>
        <button id="sim" onclick="aceitou()">Sim</button>
        <button id="nao" onclick="sumir()">Não</button>
    </div>

    <div id="mensagem">
        <h2>Eu sabia que você diria sim!</h2>
        <p>
            Você faz os meus dias mais felizes e transforma os momentos simples em lembranças especiais.
            Prometo cuidar de você, respeitar você e estar ao seu lado nos dias bons e nos difíceis.
            Que esse seja apenas o começo de uma linda história. Eu te amo!
        </p>
    </div>
</div>

<script>
function sumir(){
    document.getElementById("nao").style.display="none";
}

function aceitou():void {
    document.getElementById("conteudo-principal").style.display="none";
    document.getElementById("mensagem").style.display="block";
}
</script>

</body>
</html>
