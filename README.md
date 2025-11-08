# Rota Inteligente: Otimização de Entregas com Algoritmos de IA

## 👩‍💻 Autora
Giulia Pereira

## 🎯 Descrição do Problema
A empresa fictícia **Sabor Express** enfrenta dificuldades em gerenciar suas entregas durante horários de pico. Os entregadores definem rotas manualmente, o que causa atrasos e alto consumo de combustível.

O desafio é desenvolver uma **solução de Inteligência Artificial** que sugira as melhores rotas e agrupe entregas próximas, otimizando tempo e custo.

---

## 🧩 Objetivo
Criar um sistema inteligente que utilize algoritmos de **busca (A*)** e **aprendizado não supervisionado (K-Means)** para:
- Encontrar o caminho mais curto entre pontos de entrega;
- Agrupar entregas próximas em zonas eficientes.

---

## 🧠 Algoritmos Utilizados
### 🔹 A* (A Estrela)
O algoritmo A* é usado para encontrar o **menor caminho entre dois pontos**. Ele combina custo real + estimativa (heurística), o que o torna eficiente para mapas e rotas.

### 🔹 K-Means
O algoritmo K-Means faz **agrupamento de entregas próximas**. Ele separa as entregas em grupos (clusters), permitindo que um entregador fique responsável por cada zona.

---

## 🗺️ Representação do Grafo
A cidade foi representada como um **grafo completo**, onde:
- Cada nó representa um ponto de entrega;
- Cada aresta tem um peso baseado na **distância euclidiana** entre os pontos.

---

## 📊 Resultados
O sistema gera um mapa com:
- **Pontos coloridos** representando grupos de entregas (clusters);
- **Linhas tracejadas** mostrando a rota mais curta calculada pelo A*.

**Vantagens obtidas:**
- Redução no tempo total de entrega;
- Economia de combustível;
- Planejamento mais eficiente das rotas.

---

## ⚙️ Tecnologias Utilizadas
- Python 3  
- Google Colab  
- Bibliotecas: `numpy`, `matplotlib`, `scikit-learn`, `networkx`

---

## 🚀 Como Executar
1. Acesse [Google Colab](https://colab.research.google.com/)
2. Cole o código do projeto e execute as células.
3. Visualize o gráfico gerado com as rotas e agrupamentos.

---

## 💬 Conclusão
A combinação dos algoritmos **A\*** e **K-Means** demonstra como conceitos básicos de Inteligência Artificial podem ser aplicados para resolver problemas reais de logística e otimização de entregas.

Essa abordagem é escalável e pode ser aprimorada com dados de trânsito em tempo real e aprendizado por reforço no futuro.
