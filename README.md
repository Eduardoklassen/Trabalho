# Eduardo-Klassen
 Trabalho
# AtividadeInformatica
 Trabalho 
# Programa informativo sobre John von Neumann

Este repositório contém um programa Python interativo que apresenta informações sobre John von Neumann, suas contribuições para a, ciência da computação e outras áreas do conhecimento.

```python
# Programa informativo sobre John von Neumann

def resumo():
    """Retorna o resumo sobre John von Neumann."""
    return "João von Neumann para a ciência da computação foi a formulação da Arquitetura de Von Neumann, e o primeiro rascunho de um relatório sobre o EDVAC."

def doutorado():
    """Retorna informações sobre o doutorado de John von Neumann."""
    return "Obteve seu doutorado em matemática na Universidade de Budapeste."

def contribuicoes():
    """Retorna as contribuições de John von Neumann para a computação."""
    return (
        
    )

def artigos():
    """Lista os principais artigos de João von Neumann."""
    return (
        
    )

def citacoes():
    """Retorna uma citação famosa de John von Neumann."""
    return "As ciências não tentam explicar, nem sequer tentam interpretar; principalmente fazem modelos."

def sair():
    """Mensagem de encerramento."""
    return "\nObrigado pela leitura!"

def erro():
    """Mensagem para opções inválidas."""
    return "\nOpção inválida! Tente novamente."

def main():
    """Menu interativo para aprender sobre John von Neumann."""
    print("\nBoa noite! Você está aprendendo sobre João von Neumann.\n")
    continuar = True

    while continuar:
        try:
            # Exibe o menu
            opcao = int(
                input(
                    """
Digite o número correspondente ao menu que você deseja acessar:
1 - Resumo
2 - Doutorado
3 - Contribuições
4 - Principais Artigos
5 - Citações
6 - Sair\n
"""
                )
            )

            # Processa a opção escolhida
            if opcao == 1:
                print("\n1 - Resumo")
                print(resumo())
            elif opcao == 2:
                print("\n2 - Doutorado")
                print(doutorado())
            elif opcao == 3:
                print("\n3 - Contribuições")
                print(contribuicoes())
            elif opcao == 4:
                print("\n4 - Principais Artigos")
                print(artigos())
            elif opcao == 5:
                print("\n5 - Citações")
                print(citacoes())
            elif opcao == 6:
                print(sair())
                continuar = False
            else:
                print(erro())
        except ValueError:
            print("\nPor favor, insira um número válido.")

# Executa o programa principal
if __name__ == "__main__":
    main()




