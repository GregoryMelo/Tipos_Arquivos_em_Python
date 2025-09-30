# 📂 Tipos de Arquivos em Python

Este repositório é um guia rápido sobre como **trabalhar com arquivos no Python**, utilizando a função `open()` e os principais modos de abertura.  
A ideia é servir como referência simples para consulta e prática.

---

## 🔑 O que você vai encontrar
- Explicação da função **`open()`**.  
- Exemplos de leitura e escrita em arquivos.  
- Lista dos **modos de abertura de arquivos** (`r`, `w`, `x`, `a`, `b`, `t`, `+`).  
- Exemplos práticos de como manipular arquivos.  

---

## 📝 Exemplos básicos

Abrindo e lendo um arquivo:

```python
arquivo = open("teste.txt")
print(arquivo.read())       # Lê todo o conteúdo
print(arquivo.readline())   # Lê uma linha por vez

```
Escrevendo em um arquivo:
```python
conteudo = "Estou inserindo esse conteúdo no arquivo de texto"

arquivo = open("texto.txt", "w")  # modo escrita
arquivo.write(conteudo)
arquivo.close()
```
## 📌 Modos de abertura

- `'r'` → leitura (padrão)  
- `'w'` → escrita (sobrescreve conteúdo)  
- `'x'` → criação de arquivo (falha se já existir)  
- `'a'` → escrita (anexa conteúdo ao final)  
- `'b'` → modo binário  
- `'t'` → modo texto (padrão)  
- `'+'` → leitura e escrita  
