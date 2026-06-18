# 🛗 Simulador de Sistema de Elevadores

**Trabalho Acadêmico**

## 👨‍🎓 Integrantes

* Gilmar Vitor Soares de Oliveira
* Josué Teixeira Ferreira Filho

---

## 📖 Descrição

Este projeto consiste em um simulador de sistema de elevadores desenvolvido em Python. O objetivo é demonstrar conceitos fundamentais de programação, como estruturas de dados, funções, laços de repetição, condicionais e tratamento de exceções.

O sistema simula o funcionamento de dois elevadores em um prédio com múltiplos andares, escolhendo automaticamente o elevador mais próximo para atender às chamadas dos usuários.

---

## 📋 Funcionalidades

* Dois elevadores independentes (A e B).
* Escolha automática do elevador mais próximo.
* Movimentação andar por andar.
* Eventos aleatórios durante o percurso.
* Validação dos andares de origem e destino.
* Exibição das descrições dos andares.
* Tratamento de erros para entradas inválidas.
* Possibilidade de realizar múltiplas chamadas sem reiniciar o programa.

---

## 🏢 Estrutura do Prédio

| Andar | Descrição                    |
| ----- | ---------------------------- |
| -2    | Subsolo 2 - Garagem inferior |
| -1    | Subsolo 1 - Garagem superior |
| 0     | Térreo - Entrada principal   |
| 1     | 1º Andar - Salas de aula     |
| 2     | 2º Andar - Laboratórios      |
| 3     | 3º Andar - Biblioteca        |
| 4     | 4º Andar - Administração     |

---

## 🎲 Eventos Simulados

Durante a movimentação dos elevadores, podem ocorrer eventos aleatórios para tornar a simulação mais dinâmica:

* 🎵 Música ambiente iniciada.
* ☕ Um professor entrou no elevador.
* 📚 Um aluno carregando livros embarcou.
* 🚪 Porta abrindo e fechando.
* 🔔 Campainha tocou.
* 🤖 Sistema realizou autodiagnóstico.
* ✨ Viagem tranquila.
* 🎉 Passageiro encontrou um amigo.

Cada movimentação possui uma probabilidade de 40% de gerar um evento aleatório.

---

## ⚙️ Como Funciona

1. O usuário informa o andar onde está.
2. O usuário informa o andar de destino.
3. O sistema verifica se os andares são válidos.
4. O elevador mais próximo é selecionado automaticamente.
5. O elevador se desloca até o andar de origem.
6. O usuário embarca.
7. O elevador segue até o andar de destino.
8. O sistema informa a chegada e exibe a descrição do local.
9. O usuário pode realizar uma nova chamada ou encerrar o programa.

---

## 🚀 Como Executar

### Pré-requisitos

* Python 3.8 ou superior instalado na máquina.

### Executando o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/simulador-elevador.git
```

2. Entre na pasta do projeto:

```bash
cd simulador-elevador
```

3. Execute o programa:

```bash
python elevador.py
```

---

## 📂 Estrutura do Projeto

```text
simulador-elevador/
│
├── elevador.py
└── README.md
```

---

## 🛠 Tecnologias Utilizadas

* Python 3
* Biblioteca padrão `random`

---

## 📚 Conceitos Aplicados

Este projeto utiliza diversos conceitos fundamentais da programação:

* Variáveis e constantes
* Listas
* Dicionários
* Funções
* Estruturas condicionais (`if`, `else`)
* Laços de repetição (`while`)
* Tratamento de exceções (`try/except`)
* Geração de números aleatórios
* Simulação de sistemas

---

## 💻 Exemplo de Execução

```text
=== SISTEMA DE ELEVADORES ===

Andar onde você está: 1
Andar de destino: 4

Chamada recebida

Elevador escolhido: A
Embarque no elevador A

Elevador A passando pelo andar 1
📚 Um aluno carregando livros embarcou.

Usuário embarcou

Elevador A passando pelo andar 2
Elevador A passando pelo andar 3
🔔 Campainha tocou.
Elevador A passando pelo andar 4

Entrega ao andar 4
Local: 4º Andar - Administração
Viagem finalizada com sucesso
```

---

## 🔮 Possíveis Melhorias

Como evolução futura do projeto, podem ser implementadas as seguintes funcionalidades:

* Controle de direção dos elevadores.
* Sistema de fila de chamadas.
* Simulação de múltiplos usuários.
* Controle de capacidade dos elevadores.
* Estatísticas de utilização.
* Interface gráfica.
* Mais andares e elevadores.
* Persistência de dados em arquivos ou banco de dados.

---

## 🎯 Objetivo Acadêmico

Este projeto foi desenvolvido com fins educacionais para praticar conceitos de programação em Python, modelagem de sistemas e resolução de problemas utilizando lógica computacional.

---

## 📄 Licença

Este projeto foi desenvolvido exclusivamente para fins acadêmicos e de aprendizagem.
