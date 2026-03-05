programa {
  funcao inicio() {
    inteiro x, y

    escreva("Digite o valor inicial (x): ")
    leia(x)
    escreva("Digite o valor final (y): ")
    leia(y)

    // Chamada da função e exibição do resultado
    escreva("A soma do intervalo é: ", soma_intervalo(x, y))
  }

  funcao inteiro soma_intervalo(inteiro x, inteiro y) {
    inteiro resultado
    
    // Fórmula da soma de uma Progressão Aritmética (PA)
    // Soma = (Primeiro + Último) * Quantidade de números / 2
    resultado = (x + y) * (y - x + 1) / 2
    
    retorne resultado
  }
}
