# Uma-simples-p-gina-web-feita-com-html5-CSS3-e-js
<!doctype html5>
<html lang="pt-br">
<head>
<meta charset="utf-8">
 <meta http-equiv="X-UA-Compatible" content="IE=edge"> <meta name="viewport" content="width=device-width", initial-scale="1.0">
 <meta name="author" content="Diogo Alfredo Cabaça Umba|Peter Steel Man Hardy">
 <title>Modelo de exercício</title>
 <style type="text/css">
 body{ background-color:rgb(70,142,236); font:12pt serif; }
 header{color:white; text-align:center;}
 input#button{ color:white; background-color:red; border:2px solid red; border-radius:10px; box-shadow:3px 3px 10px #cacaca;}
 section{background:white;border-radius:18px; padding:15px;width:500px; margin:auto;box-shadow:3px 3px 10px rgb(0,0,163); }
 footer{color:white;text-align:center; font-style:italic; }
 </style>
 </head>
 <body>
 <header>
 <h1><i>Média</i></h1>
 </header>
 <section>
 <div>
  <p><input type="number" name="txtn1" id="txtn1" placeholder="Digite a primeira nota"></p>
 <p><input type="number" name="txtn2" id="txtn2" placeholder="Digite a segunda nota"></p>
 <p><input type="number" name="txtn3" id="txtn3" placeholder="Digite a terceira nota"></p>
 <p><input type="button" id="button" value="Calcular" onclick="calcular()"></p>
 </div>
<strong><i> <div id="res">
 <p>Calculando...</p>
 </div></i></strong>
 </section>
 <footer>
 <p>&copy;FastUniversal</p>
 </footer>
 <script type="text/javascript">
 window.alert("Esse programa foi desenvolvido por Diogo Alfredo Cabaça Umba")
 var n=[window.document.getElementById('txtn1'),window.document.getElementById('txtn2'),window.document.getElementById('txtn3'),window.document.getElementById('res'),,,,]
 function calcular(){
 if (n[0].value.length<=0 || n[1].value.length<=0 || n[2].value.length<=0){
 window.alert("[Erro] média invalida")
 n[3].innerText='Impossível calcular'
 n[3].style.color='red'
 } else{
 n[4]=Number(n[0].value)
 n[5]=Number(n[1].value)
 n[6]=Number(n[2].value)
 if (n[4]>n[5] && n[6]>n[5]){
 n[7]=(n[4]+n[6])/2
 }else if(n[4]>n[6] && n[5]>n[6]){
 n[7]=(n[4]+n[5])/2
 }else{
 n[7]=(n[5]+n[6])/2
 } res.innerText='A média dos dois maiores números é : ' +n[7]
  res.style.color='blue'
 }}</script>
 </body>
 </html>
