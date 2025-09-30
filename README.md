# 📂 Resumo sobre Manipulação de Arquivos em Python

Este repositório demonstra as principais formas de trabalhar com diferentes tipos de arquivos em Python. O código-fonte detalhado está disponível no notebook.

## 1. Manipulação de Arquivos de Texto (.txt)

-   **Abertura e Leitura**: Utiliza a função `open()` para ler arquivos. São demonstrados os métodos:
    -   `read()`: Para ler todo o conteúdo do arquivo.
    -   `readline()`: Para ler uma linha por vez.
    -   `readlines()`: Para ler todas as linhas e armazená-las em uma lista, permitindo manipulações como a ordenação (`sort()`).
-   **Modos de Abertura**: Explica os diferentes modos como `'r'` (leitura), `'w'` (escrita, sobrescreve), e `'a'` (anexar ao final).
-   **Escrita**: Mostra como usar `arquivo.write()` para gravar conteúdo em um arquivo.

## 2. Trabalhando com Arquivos CSV

-   **O que é**: Apresenta o formato CSV (Comma Separated Values) para dados tabulares.
-   **Leitura e Escrita**: Utiliza a biblioteca nativa `csv` para ler (`csv.reader`) e escrever (`csv.writer`) em arquivos `.csv`, demonstrando como pular cabeçalhos e adicionar novas linhas.

## 3. Trabalhando com Arquivos JSON

-   **O que é**: Introduz o formato JSON (JavaScript Object Notation), ideal para troca de dados com sua estrutura de chave-valor.
-   **Conversão e Manipulação**: Usa a biblioteca `json` para:
    -   `json.dumps()`: Converter um dicionário Python em uma string JSON.
    -   `json.dump()`: Salvar um dicionário diretamente em um arquivo `.json`.
    -   `json.load()`: Carregar dados de um arquivo `.json` para um dicionário Python.
    -   `json.loads()`: Converter uma string no formato JSON para um dicionário Python.

## ✅ Boas Práticas

-   **Gerenciamento de Arquivos**: Enfatiza o uso do bloco `with open(...) as ...`, que garante que o arquivo seja fechado automaticamente após o uso, tornando o código mais seguro e limpo.
