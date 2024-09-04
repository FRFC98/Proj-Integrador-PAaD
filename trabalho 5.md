1 – implemente o algoritmo de ordenação Bubble Sort usando python;

def bubble_sort(arr):
    n = len(arr)
    # Percorre todos os elementos da lista
    for i in range(n):
        # Últimos i elementos já estão no lugar
        for j in range(0, n - i - 1):
            # Troca se o elemento encontrado for maior que o próximo elemento
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]

# Exemplo de uso
lista = [64, 34, 25, 12, 22, 11, 90]
bubble_sort(lista)
print("Lista ordenada:", lista)

Comprovante da execução
![Print trabalho aula 5](https://github.com/user-attachments/assets/b6d2dbc5-9e49-4553-bca6-999bcb9c952d)
file:///C:/Users/202108055778/Pictures/Print%20trabalho%20aula%205.PNG


2 – implemente um algorítimo que imprima apenas as vogais de uma 
determinada palavra ou frase
def extrair_vogais(texto):
    # Definindo as vogais
    vogais = "aeiouAEIOU"
    
    # Usando uma lista para armazenar as vogais encontradas
    resultado = [caractere for caractere in texto if caractere in vogais]
    
    # Convertendo a lista para uma string e imprimindo
    print("".join(resultado))

# Exemplo de uso
texto = "Hoje vou trabalhar"
extrair_vogais(texto)

oeouaaa

=== Code Execution Successful ===




file:///C:/Users/202108055778/Pictures/Screenshots/trabalho%205%20sequ%C3%AAncia%20de%20vogais.PNG
![trabalho 5 sequência de vogais](https://github.com/user-attachments/assets/ea392877-3742-4c30-b9c5-cd5d3014c033)
