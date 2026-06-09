JavaScript
// SELEÇÃO DOS ELEMENTOS PRINCIPAIS
var display = document.getElementById('display');
var buttons = document.querySelectorAll('.btn');
var clearButton = document.getElementById('clear'); // Seleciona o botão 'C' pelo ID

// ARMAZENA OS NÚMEROS E OPERADORES DIGITADOS
var currentInput = '';

console.log("Sistema iniciado. Aguardando entrada do usuário...");

//-----------------------------------------------------------------
// Percorrer todos os botões numéricos e operadores (classe .btn)
//-----------------------------------------------------------------
for (var i = 0; i < buttons.length; i++) {
    buttons[i].addEventListener('click', function(){
        var value = this.textContent;
        console.log("Botão clicado:", value);

        if (value === '=') {
            // Executa o cálculo matemático com o que está na tela
            try {
                // eval calcula a string (ex: "2+5*3")
                var resultado = eval(currentInput); 
                
                display.value = resultado;       // CORRIGIDO: Usa-se .value para input
                currentInput = resultado.toString(); 
            } catch (error) {
                display.value = "Erro";
                currentInput = '';
            }
        } else {
            // Se for número ou operador comum, acumula
            currentInput += value;
            display.value = currentInput;       // CORRIGIDO: Usa-se .value para input
        }
    });
}

//-----------------------------------------------------------------
// Evento separado para o botão 'C' (Limpar), já que ele não tem a classe .btn
//-----------------------------------------------------------------
clearButton.addEventListener('click', function() {
    console.log("Botão Limpar clicado");
    currentInput = '';
    display.value = ''; // Limpa a tela
});
