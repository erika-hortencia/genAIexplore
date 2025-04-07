# genAIexplore

Este repositório apresenta uma solução prática de reconhecimento de texto (OCR) a partir de imagens usando a ferramenta **Azure AI Vision**. O foco do projeto é mostrar como imagens cotidianas contendo texto podem ser analisadas automaticamente com tecnologias modernas.

---

## 📁 Estrutura do Projeto

- `inputs/` — Contém as imagens utilizadas para análise (ex: fotos de placas, capas de livros, quadros de aula).
- `output/` — Arquivos `.txt` com o resultado do OCR de cada imagem.
- `readme.md` — Este documento com a descrição do projeto, aprendizados e possibilidades futuras.

---

## 🚀 Tecnologias Utilizadas

| Ferramenta | Descrição |
|-----------|-----------|
| Azure AI Vision | Serviço da Microsoft para extração de texto via OCR |
| Copilot / GPT | Auxiliar para organizar e interpretar os textos extraídos |

---

## 📝 Processo

1. Acesse o [Vision Studio](https://portal.azure.com/).
2. Escolha a opção **"Extract text from image"**.
3. Faça upload das imagens da pasta `inputs`.
4. O resultado pode ser salvo como `.txt` e foi armazenado na pasta `output`.
5. Os textos foram interpretados com ajuda do Copilot e GPT para gerar insights adicionais.

---

## ✨ Exemplos

### 📌 Imagem 1 - Placa de Loja
Reconhecido:
```
CAFETERIA DO BAIRRO
Aberto todos os dias
Seg a Sex: 7h - 20h
Sáb e Dom: 8h - 18h
Promoção: Café + Pão de Queijo por R$5,00
```

### 📘 Imagem 2 - Capa de Livro
Reconhecido:
```
Título: Aprendizado de Máquina com Python
Autor: João Silva
Editora: Ciência Moderna
Resumo: Guia prático para quem deseja aprender técnicas modernas de machine learning com exemplos em Python.
```
---

## 🤖 Aprendizados

- O Azure Vision Studio é intuitivo e eficaz para OCR em português.
- Pequenos ruídos na imagem não comprometem os resultados.
- Ferramentas como GPT e Copilot ajudam a transformar dados brutos em conhecimento.

---

## 🔮 Possibilidades Futuras

- Aplicações em acessibilidade (leitura de placas para deficientes visuais)
- Digitalização de conteúdo impresso
- Automatização de processos de cadastro a partir de documentos físicos

---

