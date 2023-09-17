# **Automação de Vendas**

### **Sobre**

Este projeto consiste em um script para automação de processos relacionados a indicadores de vendas de lojas. Ele lê dados de arquivos Excel e CSV, realiza análises e operações de dados, e envia e-mails com os resultados.

### **Bibliotecas Utilizadas:**

- **`pandas`**: Para manipulação e análise de dados.
- **`pathlib`**: Para manipulação de caminhos de arquivos e diretórios.
- **`smtplib`** e módulos **`email.*`**: Para enviar e-mails com os resultados.
- **`os`**: Para operações relacionadas ao sistema operacional.

### **Pré-requisitos:**

- **[Python 3.8+](https://www.python.org/downloads/)**
- **[Jupyter Notebook](https://jupyter.org/install)**

### **Como Instalar:**

1. **Instalar Python**:
    - Acesse **[Python Downloads](https://www.python.org/downloads/)** e faça o download da versão recomendada.
    - Siga as instruções do instalador. Lembre-se de marcar a opção "Add Python to PATH" durante a instalação.
2. **Instalar Jupyter Notebook**:
    - Abra o terminal ou prompt de comando e execute:
        
        ```
        pip install jupyter
        ```
        
3. **Instalar Bibliotecas Necessárias**:
    - Ainda no terminal ou prompt de comando, instale as bibliotecas usadas neste projeto:
        
        ```
        pip install pandas
        ```
        
4. **Clone este repositório** ou faça o download dos arquivos.
5. Abra o Jupyter Notebook navegando até o diretório do projeto e execute:
    
    ```
    jupyter notebook
    ```
    
6. No navegador, abra o arquivo **`Automacao de Processo.ipynb`**.

### **Como Executar:**

1. Dentro do Jupyter Notebook, vá até a célula que deseja executar e pressione **`Shift+Enter`**.
2. Siga as instruções contidas nas células de markdown e execute as células de código em ordem.

### **Estrutura de Arquivos:**

- **`Bases de Dados`**: Contém os arquivos de dados utilizados para a análise.
- **`Backup Arquivos Lojas`**: Contém backups ou arquivos relacionados às lojas.
