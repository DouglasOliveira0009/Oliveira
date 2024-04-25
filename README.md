EXERCICIO 2 ARRAY

let comidasPreferidas = ['pizza', 'hamburguer', 'sushi', 'lasanha', 'churrasco'];

console.log('a) Array completo:', comidasPreferidas);

console.log('b) Essas são as minhas comidas preferidas:');
comidasPreferidas.forEach(comida => {
console.log(comida);
});

let comidaUsuario = prompt('Qual sua comida preferida?');
comidasPreferidas[1] = comidaUsuario;


console.log('c) Nova lista de comidas preferidas:', comidasPreferidas);

EXERCICIO 3 ARRAY

let listaDeTarefas = [];

for (let i = 0; i < 3; i++) {
  let tarefa = prompt(`Digite a tarefa ${i + 1}:`);
  listaDeTarefas.push(tarefa);
}

console.log('Lista de Tarefas:', listaDeTarefas);

let indiceRealizada = parseInt(prompt('Digite o índice da tarefa realizada (0, 1 ou 2):'));

listaDeTarefas.splice(indiceRealizada, 1);

console.log('Lista de Tarefas após remoção:', listaDeTarefas);

DESAFIO 1 ARRAY 

function dividirFraseEmPalavras(frase) {

    return frase.split(' ');
  }
  
  let frase = prompt('Digite uma frase:');
  let arrayPalavras = dividirFraseEmPalavras(frase);
  console.log('Array de palavras:', arrayPalavras);


  DESAFIO 2 ARRAY 

*let frutas = ["Banana", "Morango", "Abacaxi", "Laranja", "Ameixa"];

let indiceAbacaxi = frutas.indexOf("Abacaxi");

console.log("O índice da palavra 'Abacaxi' é:", indiceAbacaxi);
console.log("O tamanho do array é:", frutas.length);




DESAFIO FUNÇÃO 

function somarNumeros(n1, n2){
    let soma = n1=n2
    return soma
}

let resultado = somarNumeros(1, 1)
console.log(resultado)

