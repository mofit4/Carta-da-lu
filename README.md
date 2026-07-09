<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Para Luana ❤️</title>

<style>
body{
    margin:0;
    font-family:Arial, Helvetica, sans-serif;
    background:linear-gradient(135deg,#ff7eb3,#ff4f81);
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    color:white;
}

.container{
    text-align:center;
    max-width:700px;
    padding:30px;
}

h1{
    font-size:48px;
    margin-bottom:10px;
}

p{
    font-size:22px;
}

button{
    margin-top:25px;
    padding:15px 35px;
    font-size:20px;
    border:none;
    border-radius:30px;
    background:white;
    color:#ff2d75;
    cursor:pointer;
    transition:.3s;
}

button:hover{
    transform:scale(1.08);
}

.carta{
    display:none;
    margin-top:30px;
    background:white;
    color:#444;
    padding:25px;
    border-radius:20px;
    box-shadow:0 10px 30px rgba(0,0,0,.2);
    animation:aparecer .8s;
    line-height:1.8;
}

@keyframes aparecer{
from{opacity:0;transform:translateY(20px);}
to{opacity:1;transform:translateY(0);}
}
</style>
</head>

<body>

<div class="container">

<h1>Luana ❤️</h1>

<p>Tenho uma notícia importante para você...</p>

<button onclick="abrirCarta()">Clique aqui 💌</button>

<div class="carta" id="carta">

<h2>Feliz Aniversário! 🎉❤️</h2>

<p>
Lu, meu amor,
</p>

<p>
Venho desejar os parabéns, pois agora você terá que ter muita paciência para aguentar minhas gracinhas enquanto a gente permanecermos juntos nesta vida. 😅❤️
</p>

<p>
Brincadeiras à parte, espero que seu dia seja tão especial quanto você é para mim. Que nunca faltem motivos para sorrir, realizar seus sonhos e ser feliz.
</p>

<p>
Obrigado por existir e por fazer parte da minha vida. Que este seja apenas mais um aniversário entre tantos que ainda vamos comemorar lado a lado.
</p>

<h2>Eu te amo! ❤️</h2>

</div>

</div>

<script>
function abrirCarta(){
document.getElementById("carta").style.display="block";
}
</script>

</body>
</html>
