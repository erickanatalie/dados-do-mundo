# 🌍 Projeto: Dados do Mundo

Este projeto permite consultar e gerar um relatório em PDF com informações básicas de qualquer país, usando a [REST Countries API](https://restcountries.com/).

🔍 Informações coletadas:
- Nome oficial
- Capital
- Região
- População
- Moeda(s)
- Bandeira (URL)

📄 O relatório gerado é salvo como PDF e pode ser baixado no Colab.

---

## 🚀 Como usar

### ▶️ Execute direto no Google Colab:
👉 [Abrir no Google Colab](https://colab.research.google.com/)

### 1. Digite o nome do país (em português ou inglês)
Exemplos válidos:
- brasil
- alemanha
- moçambique
- japão

### 2. O sistema traduz (se necessário), consulta a API e exibe os dados no console.

### 3. Um PDF é gerado automaticamente com os dados e pode ser baixado.

---

## 🛠️ Tecnologias utilizadas
- Python 3
- [requests](https://pypi.org/project/requests/)
- [fpdf](https://pypi.org/project/fpdf/)
- Google Colab (para execução online)

---

## 📎 Exemplo de saída
```text
📘 Dados do Mundo:
📄 Nome oficial: Federal Republic of Germany
🏛️ Capital: Berlin
🌍 Região: Europe
👥 População: 83240525
💰 Moeda(s): euro
🏳️ Bandeira: https://flagcdn.com/w320/de.png
📄 PDF gerado: germany_dados.pdf
