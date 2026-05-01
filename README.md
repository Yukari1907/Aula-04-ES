# Aula-04-ES

Exercício Prático — Hands-on!
🚀 Missão: Construir o SRS do "FIAP Marketplace"
Contexto: A FIAP quer criar um marketplace interno onde alunos podem vender produtos artesanais entre si (como um Etsy da FIAP 🛒).
No Google Colab ou VS Code, você vai:
Parte 1 — Estender o código Python da aula
Copie o código da aula e adicione ao SRS do FIAP Marketplace:
Pelo menos 3 Requisitos Funcionais usando o modelo RF-XXX
Sugestões: Cadastro de produto, Busca por categoria, Checkout, Avaliação do vendedor
Pelo menos 2 Requisitos Não-Funcionais
Sugestões: Disponibilidade 99.9%, Tempo de resposta da busca, Conformidade com LGPD
Parte 2 — Análise crítica
Adicione uma função validar_requisito(rf) que verifica se o requisito:
[ ] Tem descrição com mais de 20 caracteres (evitar requisitos vagos)
[ ] Tem pré-condição definida (não vazia)
[ ] Tem critério mensurável (checar se tem números na descrição)
def validar_requisito(rf: RequisitoFuncional) -> dict:
    """
    Valida se um requisito funcional segue as boas práticas.
    Retorna um dict com os resultados da validação.
    """
    resultados = {}
    
    # TODO: Implemente as validações aqui!
    # Dica 1: len(rf.descricao) > 20
    # Dica 2: rf.pre_condicao != ""
    # Dica 3: any(char.isdigit() for char in rf.descricao)
    
    return resultados
Parte 3 — Desafio extra ⭐
Crie um método exportar_markdown(srs) que gera o SRS em formato Markdown, pronto para ser colado no Confluence ou Notion da sua empresa!
