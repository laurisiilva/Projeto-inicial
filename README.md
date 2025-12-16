alert("Boas vindas ao jogo do número secreto");
let numeroSecreto = 26;
console.log (numeroSecreto)
let chute = prompt("Escolha um número entre 1 e 30");
console.log('valor do chute:' + chute);

//se chute for igual ao numero secreto 
if (chute == numeroSecreto) {
    alert('Isso ai! Você descobriu o número secreto ' + numeroSecreto );
} 
else {
   console.log ('Valor do numero secreto:' + numeroSecreto);
    alert ('Você errou, o número secreto era ' + numeroSecreto);
}
