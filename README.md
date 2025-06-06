```markdown
# 🧾 Fintrack

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Code Style](https://img.shields.io/badge/code%20style-flake8-blue)](https://flake8.pycqa.org/)

**Fintrack** é um sistema simples para gerenciar gastos e organizar compras de forma automática ou manual. Ideal para quem quer manter o controle financeiro sem complicação.

---

## ✨ Funcionalidades

- ✅ Cadastro manual de lançamentos  
- ✅ Importação automática via URL de Nota Fiscal Eletrônica (NFC-e)  
- ✅ Armazenamento dos dados em banco de dados local  
- ✅ Categorização de compras  

---

## 🔍 Como Funciona?

Ao inserir a URL de uma nota fiscal eletrônica, o Fintrack utiliza um **crawler** para buscar e extrair os detalhes da compra (como produtos, valores e datas) diretamente da NFC-e. Essas informações são armazenadas automaticamente no banco de dados para consulta posterior.

---

## 🛠 Tecnologias Utilizadas

- 🐍 Python  
- 🧮 Pandas  
- 🌐 BeautifulSoup  
- 🗃️ MySQL  
- ✅ Flake8 (padrão de código)  

---

## ⚙️ Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/<seu-usuario>/fintrack.git
   cd fintrack
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Inicie o sistema:
   ```bash
   python project_up.py
   ```

---

## 🧪 Teste Agora

Você pode testar o funcionamento com esta nota fiscal real de exemplo:

👉 [Nota Fiscal Exemplo](https://www.fazenda.pr.gov.br/nfce/qrcode?p=41250317919277000115650010001306301374878193%7C2%7C1%7C1%7CEB7E8A603616843BE533EFBA8F854AF2CD1A498C)

---


## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma _issue_ ou enviar um _pull request_ com melhorias, correções ou novas funcionalidades.

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

> Fintrack – Simplifique sua organização financeira. 💰
