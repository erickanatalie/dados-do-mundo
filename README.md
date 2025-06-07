# dados-do-mundo
Um projeto simples em Python para buscar **informações de países** a partir do nome (em português ou inglês) e gerar um **relatório em PDF** com os dados retornados pela API pública [REST Countries](https://restcountries.com/).
## ✨ Funcionalidades

- Entrada do nome de um país (em português ou inglês)
- Tradução automática para o nome aceito pela API
- Coleta de dados:
  - Nome oficial
  - Capital
  - Região
  - População
  - Moeda(s)
  - Bandeira
- Geração de um **relatório em PDF**
- Download automático no Google Colab

---

## 📦 Tecnologias usadas

- Python 3
- Biblioteca [`requests`](https://pypi.org/project/requests/)
- Biblioteca [`fpdf`](https://pypi.org/project/fpdf/)
- Google Colab (para execução e download)

---

## ▶️ Como executar

1. Acesse o notebook no Google Colab
2. Execute as células do topo até o final
3. Digite o nome de um país, por exemplo: `Brasil`, `Alemanha`, `Japão`, `Moçambique`
4. O PDF será gerado e baixado automaticamente

---

## 📝 Exemplo de uso

```bash
Digite o nome de um país (em português ou inglês): brasil
📄 PDF gerado: brasil_dados.pdf
