```markdown
# Trabalho Prático 1: Perceptron e KNN em Prática

Repositório dedicado à entrega da Atividade Prática Individual (AT1) de Aprendizagem de Máquina, desenvolvida em **Jupyter Notebook (`at1_am.ipynb`)** utilizando a biblioteca **NumPy** para operações vetorizadas.

## Tecnologias Utilizadas
- Python 3.14
- Jupyter Notebook (`.ipynb`)
- NumPy (Processamento vetorizado)
- Matplotlib (Visualização de dados)
- Gerenciador de projetos: `uv`

---

## Conteúdo do Notebook (`at1_am.ipynb`)

O notebook está dividido em seções claras correspondentes aos três desafios propostos:

### Desafio 1: Classificação Binária com Perceptron Treinável
- **Contexto:** Mecanismo de triagem preliminar para detectar transações financeiras com potencial risco de fraude.
- **Implementação:** Função de treinamento baseada na regra de ajuste de pesos de Rosenblatt (com pesos e viés inicializados em `1.0`), função de inferência com função degrau e validação com transações de teste em tempo real.

### Desafio 2: Predição de Risco de Churn com Classificador KNN
- **Contexto:** Antecipação de risco de cancelamento (churn) de clientes corporativos (SaaS).
- **Implementação:** Classificador KNN totalmente vetorizado com suporte às métricas de distância **Euclidiana** e **Manhattan** (utilizando `np.linalg.norm`), cálculo de vizinhos mais próximos e votação por maioria (moda).

### Desafio 3: Recomendação de Servidores Cloud por Similaridade Espacial
- **Contexto:** Ferramenta de dimensionamento automático (*sizing*) de máquinas virtuais com base em hardware (vCPUs, Memória RAM e SSD).
- **Implementação:** Similaridade espacial baseada em distância geométrica euclidiana para encontrar os servidores mais próximos do perfil de hardware demandado no catálogo.

---

## Como Executar o Projeto

1. Clone o repositório ou abra a pasta no VS Code.
2. Certifique-se de que o ambiente virtual está ativado e as dependências instaladas:
   ```bash
   source .venv/bin/activate
   uv pip install numpy matplotlib jupyter ipykernel

```

3. Abra o arquivo `at1_am.ipynb`.
4. Selecione o kernel do Python associado ao ambiente virtual (`.venv`).
5. Execute todas as células em ordem (`Restart Kernel and Run All Cells`).

```
