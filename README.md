# Cavalheiros-de-Shaka
# Lista de praticantes de musculação
praticantes = []

# Função para adicionar um novo praticante
def adicionar_praticante(nome, idade, nivel):
    praticante = {
        "nome": nome,
        "idade": idade,
        "nível": nivel  # iniciante, intermediário, avançado
    }
    praticantes.append(praticante)
    print(f"{nome} adicionado à lista!")

# Função para mostrar todos os praticantes
def mostrar_praticantes():
    print("\nLista de Praticantes de Musculação:")
    for i, p in enumerate(praticantes, start=1):
        print(f"{i}. {p['nome']} - {p['idade']} anos - Nível: {p['nível']}")

# Exemplo de uso
adicionar_praticante("Oscar", 25, "intermediário")
adicionar_praticante("Oscar", 30, "avançado")
adicionar_praticante("Oscar", 19, "iniciante")

mostrar_praticantes()


