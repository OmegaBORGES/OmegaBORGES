programa
{
	inclua biblioteca Matematica --> mat \\pergunta com raiz quadrada bem simples
	
	funcao inicio()
	{
		inteiro resultado = 2
		real numero
		real raiz

		escreva("Qual a raiz quadrada de 4?\n")

	faca{
		escreva("Resultado: ")
		leia(resultado)
	se(resultado != 2){
		escreva("Você errou! Tente novamente\n")
	}
	}
	
	enquanto(resultado != 2)
	escreva("\nVocê acertou!\n")
	numero = 4
		raiz = mat.raiz(numero, 2) // Obtém a raíz quadrada do número
		
		escreva("A raíz quadrada de ", numero , " é: ", raiz, "\n")
	
	}
}
