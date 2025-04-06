# AC2 - Laptop Analysis 2024

Repositório criado para a Atividade Contínua 2 - Análise de Dados 📊

# 💻 Análise de Laptops Best Buy - 2024

Este projeto realiza uma análise exploratória de um conjunto de dados de laptops disponíveis na loja Best Buy em 2024. O objetivo é entender padrões de preço, satisfação do cliente e diversidade de marcas.

Através de gráficos intuitivos e insights de negócios, conseguimos identificar oportunidades de otimização e compreender melhor o comportamento de consumo de laptops no mercado atual.

## 🔍 Objetivo do Projeto

Realizar uma análise exploratória de dados de laptops, visando:
- Compreender a distribuição de preços por marca
- Avaliar a satisfação dos consumidores por meio das avaliações
- Identificar marcas mais populares
- Tratar e preparar os dados ausentes para análise confiável

## 📊 Análises Realizadas

1️⃣ **Distribuição das Avaliações dos Laptops**  
Visualização da frequência de avaliações para entender a percepção geral dos consumidores.

2️⃣ **Preço Médio por Marca**  
Gráfico de barras comparando o valor médio dos laptops por marca. Ideal para perceber o posicionamento das marcas no mercado.

3️⃣ **Avaliação x Preço (com tamanho proporcional ao número de avaliações)**  
Gráfico de dispersão que mostra a relação entre o preço dos laptops e sua média de avaliação. Quanto maior o ponto, maior o número de avaliações — ótimo para entender produtos populares e bem avaliados.

4️⃣ **Quantidade de Laptops por Marca**  
Gráfico horizontal mostrando a presença de cada marca no dataset.

## 🛠️ Tecnologias Utilizadas
- **Python** para manipulação e análise de dados
- **Pandas** para tratamento e estruturação dos dados
- **Matplotlib & Seaborn** para visualizações estáticas e personalizadas

## 📂 Estrutura do Código
1. **Carregamento do Dataset**
2. **Tratamento de valores ausentes**
   - Preenchimento de preços com a média por marca
   - Preenchimento de dados categóricos com "Desconhecido"
3. **Análise Exploratória**
   - Análise estatística básica
   - Gráficos de distribuição, barras e dispersão
4. **Geração de Insights**

## 📈 Principais Descobertas
- A maioria dos laptops possui avaliações entre **4.5 e 4.7**, indicando alta satisfação do consumidor.
- Marcas apresentam variação significativa no preço médio, revelando diferentes nichos de mercado.
- A relação entre **preço e avaliação não é linear**, mostrando que preço alto não garante alta satisfação.
- Algumas marcas estão super representadas, enquanto outras aparecem em menor volume.
- Os dados brutos apresentavam valores ausentes que foram tratados cuidadosamente para manter a integridade da análise.

## 🧠 Sugestões de Melhoria
- Realizar análise mais aprofundada por especificação técnica (ex: RAM, processador, armazenamento).
- Cruzar os dados com fontes externas de benchmark para enriquecer os insights.
- Adicionar dashboards interativos com Plotly ou Streamlit.
- Implementar modelos preditivos de avaliação ou preço com base nas características dos laptops.

## 🚀 Como Rodar o Projeto
1. Clone o repositório:
   ```bash
   git clone https://github.com/Casarimdev/AC2---laptop-analysis-2024.git
   ```
2. Instale os pacotes necessários:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Execute o notebook Jupyter:
   ```bash
   jupyter notebook
   ```

Ou execute via Python:
   ```bash
   python laptop_analysis.py
   ```

---
