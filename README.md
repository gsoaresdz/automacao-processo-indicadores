# **Automação de Vendas**

Este script de automação de vendas é usado para analisar dados de vendas, calcular várias métricas de desempenho e enviar relatórios por e-mail para a gerência de cada loja e para a diretoria.

## **Requisitos**

- Python 3.7 ou superior
- Bibliotecas:
    - pandas
    - pathlib
    - smtplib
    - email.mime.multipart
    - email.mime.base
    - email.mime.text
    - email.encoders
    - os

## **Instalação**

Antes de usar este script, você precisa instalar o Python e as bibliotecas necessárias. Aqui estão as instruções:

1. Instale o Python: Você pode baixar o Python em **https://www.python.org/downloads/**. Siga as instruções na página de download para instalar o Python.
2. Instale as bibliotecas necessárias: Abra um terminal e use o seguinte comando para instalar todas as bibliotecas necessárias de uma vez:
    
    ```bash
    pip install pandas pathlib secure-smtplib email
    ```
    

## **Execução**

Para executar o script, siga estas etapas:

1. Abra um terminal.
2. Navegue até a pasta que contém o script usando o comando **`cd`**.
3. Execute o script usando o comando **`python Automacao_de_Processo.ipynb`**.

## **Funcionamento do script**

O script realiza as seguintes tarefas:

1. Carrega os dados das vendas, das lojas e dos emails dos gerentes de loja.
2. Une os dados das vendas e das lojas.
3. Agrupa as vendas por loja.
4. Calcula várias métricas de desempenho, incluindo o faturamento do dia, do ano, a diversidade de produtos vendidos e o ticket médio.
5. Envia um email para cada loja com um relatório do desempenho do dia e do ano.
6. Calcula o ranking das lojas por faturamento.
7. Envia um email para a diretoria com o ranking das lojas.
