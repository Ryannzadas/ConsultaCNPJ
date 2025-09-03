# 📊 Consulta Massiva de CNPJs via APIBrasil

Este projeto realiza consultas massivas de **CNPJs** utilizando a **API Brasil**.  
Ele foi desenvolvido em **Python 3** e possui suporte a cache local, leitura de arquivos (TXT, CSV, XLSX), extração de campos úteis e exportação para Excel e CSV.

---

## ⚙️ Funcionalidades
- Validação e limpeza automática de CNPJs.
- Consulta em lote respeitando limites da API:
  - Pausa de `0.2s` entre consultas.
  - Pausa de `2s` a cada 10 consultas.
- Cache local em JSON para evitar chamadas repetidas.
- Entrada a partir de arquivos:
  - `.txt`
  - `.csv`
  - `.xlsx`
- Saída em:
  - `results.xlsx`
  - `results.csv`
- Extração de informações principais:
  - Razão Social
  - Situação Cadastral
  - UF (Estado)

---

## 📦 Instalação

### 1. Clone o repositório ou extraia o `.rar`
```bash
git clone //github.com/Ryannzadas/ConsultaCNPJ.git
cd projeto-cnpjs
