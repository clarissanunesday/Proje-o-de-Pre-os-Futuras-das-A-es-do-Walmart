# Análise de Preços de Fechamento e Volume de Ações do Walmart

Este projeto realiza a análise dos preços de fechamento e volumes negociados das ações do Walmart, utilizando gráficos e técnicas de análise de séries temporais. O objetivo é explorar e visualizar dados financeiros de forma clara, com diferentes tipos de gráficos, como séries temporais, histogramas, gráficos de dispersão e médias móveis.

## Funcionalidades

- **Gráfico de Série Temporal**: Visualização da evolução do preço de fechamento ao longo do tempo.
- **Gráfico de Volume Negociado**: Visualização do volume de negociações ao longo do tempo.
- **Histograma de Preços de Fechamento**: Distribuição dos preços de fechamento em um período específico.
- **Gráfico de Dispersão**: Relação entre o preço de fechamento e o volume negociado.
- **Média Móvel Simples (SMA)**: Inclusão de uma média móvel simples de 20 dias para análise de tendência.

## Estrutura do Projeto

- `walmart_stock_analysis.py`: Código Python que realiza a análise e gera os gráficos.
- `README.md`: Documentação do projeto.
- `LICENSE`: Licença MIT do projeto.
- `.gitignore`: Arquivo para ignorar arquivos temporários e de configuração.

## Bibliotecas Utilizadas

O projeto faz uso das seguintes bibliotecas Python:

- **Pandas**: Para manipulação e análise de dados.
- **NumPy**: Para operações matemáticas e estatísticas.
- **Matplotlib**: Para visualização de dados.

## Como Executar o Projeto

1. **Instalar Dependências**:
   Execute o seguinte comando para instalar as bibliotecas necessárias:
   ```bash
   pip install pandas numpy matplotlib
