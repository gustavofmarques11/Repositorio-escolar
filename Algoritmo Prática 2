programa
{
    funcao inicio()
    {
        inteiro indice
        inteiro vetor[21]
        inteiro i, numero
        inteiro soma = 0
        inteiro maior, menor
        real media = 0.0

        // A - Solicitar indice
        escreva("Digite um indice entre 2 e 8: ")
        leia(indice)

        enquanto (indice < 2 ou indice > 8)
        {
            escreva("Indice invalido! Digite novamente: ")
            leia(indice)
        }

        // A e B - Multiplicar e armazenar no vetor
        i = 0

        enquanto (i < 21)
        {
            numero = i + 10
            vetor[i] = numero * indice
            i++
        }

        // C - Imprimir vetor do ultimo ao primeiro
        escreva("\nVetor em ordem inversa:\n")

        i = 20

        enquanto (i >= 0)
        {
            escreva(vetor[i], " ")
            i--
        }

        // D - Somatorio dos produtos
        i = 0

        enquanto (i < 21)
        {
            soma = soma + vetor[i]
            i++
        }

        escreva("\n\nSomatorio: ", soma)

        // E e F - Maior e menor produto
        maior = vetor[0]
        menor = vetor[0]

        i = 1

        enquanto (i < 21)
        {
            se (vetor[i] > maior)
            {
                maior = vetor[i]
            }

            se (vetor[i] < menor)
            {
                menor = vetor[i]
            }

            i++
        }

        escreva("\nMaior produto: ", maior)
        escreva("\nMenor produto: ", menor)

        // G - Media dos numeros de 10 a 30
        i = 10

        enquanto (i <= 30)
        {
            media = media + i
            i++
        }

        media = media / 21

        escreva("\nMedia dos numeros: ", media)
    }
}
