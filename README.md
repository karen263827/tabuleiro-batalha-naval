# 🛳️ Batalha Naval em C

Este projeto simula um tabuleiro de Batalha Naval utilizando a linguagem C. O objetivo é representar um tabuleiro 10x10 com dois navios de tamanho fixo (3 posições), posicionados horizontal e verticalmente. O programa inicializa o tabuleiro, posiciona os navios com validação de limites e sobreposição, e exibe o resultado no console.

---

## 📌 Funcionalidades

- Representação do tabuleiro com matriz bidimensional 10x10
- Inicialização das posições com valor `0` (água)
- Posicionamento de dois navios com valor `3` (parte do navio)
- Validação de limites do tabuleiro
- Verificação de sobreposição entre navios
- Exibição clara e organizada do tabuleiro no console

---

## 🧠 Regras de Posicionamento

- Cada navio ocupa **3 posições**
- Um navio é posicionado **horizontalmente**
- Outro navio é posicionado **verticalmente**
- As coordenadas iniciais são definidas diretamente no código
- Os navios **não podem ultrapassar os limites** do tabuleiro
- Os navios **não podem se sobrepor**

---

## 🛠️ Tecnologias Utilizadas

- Linguagem: **C**
- Compilador recomendado: `gcc`

---

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/batalha-naval-c.git
   cd batalha-naval-c
Compile o programa:

bash
gcc main.c -o batalha-naval
Execute:

bash
./batalha-naval
📂 Estrutura do Projeto
Código
batalha-naval-c/
├── main.c           # Código principal do programa
├── README.md        # Documentação do projeto
├── imagens/         # (Opcional) Prints da execução
└── docs/            # (Opcional) Relatórios ou explicações extras
