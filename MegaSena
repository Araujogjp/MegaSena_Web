function gerarNumerosMegaSena(quantidade) {
    var vetorNumeros = []; 
    var vetorGerados = [];  
    var todosNumeros = [];  
    
    for (let i = 1; i <= 60; i++) {
        todosNumeros.push(i);
    }

   
    for (let i = todosNumeros.length - 1; i > 0; i--) {
        const j = Math.floor(Math.random() * (i + 1));
        [todosNumeros[i], todosNumeros[j]] = [todosNumeros[j], todosNumeros[i]]; 
    }

    console.time("Tempo de execução");

    for (let i = 0; i < quantidade; i++) {
        var aleatorio = todosNumeros[i]; 
        vetorGerados.push(aleatorio);  
        vetorNumeros.push(aleatorio); 
    }

    console.log("Todos os números gerados", vetorGerados); 
    console.timeEnd("Tempo de execução");  

    return vetorNumeros;
    console.log("Números exclusivos", vetorNumeros);  
}
