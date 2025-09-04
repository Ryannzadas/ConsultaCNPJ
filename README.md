# 📊 Consulta CNPJ

Um projeto em **Python** para consultar informações de empresas a partir do **CNPJ**, utilizando a [API pública de CNPJs](https://publica.cnpj.ws/) ou outra fonte configurada.

## 📌 Funcionalidades
- 🔎 Consulta de dados de empresas pelo CNPJ  
- 📋 Retorno de informações como: **razão social, nome fantasia, endereço, situação cadastral e atividades econômicas (CNAEs)**  
- 🌐 Integração com API pública de CNPJs  
- 🐍 Código simples e reutilizável  

## 🛠️ Tecnologias Utilizadas
- **Python 3.8+**  
- **Requests** (para requisições HTTP)  
- **JSON** (tratamento de dados)  

## 📂 Estrutura do Projeto

ConsultaCNPJ/
├── consulta_cnpj.py # Script principal
├── utils.py # Funções auxiliares (se houver)
├── requirements.txt # Dependências do projeto
└── README.md # Documentação

## 🚀 Como Rodar o Projeto

### 1. Clone o repositório
```bash
git clone https://github.com/Ryannzadas/ConsultaCNPJ.git
cd ConsultaCNPJ
```

### 2. Crie e ative um ambiente virtual (opcional, mas recomendado)
   
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

```
### 3. Instale as dependências
````
pip install -r requirements.txt
```

````
### 4. Execute o script passando o CNPJ
```
python consulta_cnpj.py 00000000000191
````

## 📡 Exemplo de Saída
{
  "razao_social": "EMPRESA EXEMPLO LTDA",
  "nome_fantasia": "EXEMPLO",
  "cnpj": "00.000.000/0001-91",
  "situacao": "ATIVA",
  "endereco": {
    "logradouro": "Rua Exemplo",
    "numero": "123",
    "bairro": "Centro",
    "cidade": "São Paulo",
    "uf": "SP"
  },
  "cnae_principal": "6201-5/01 - Desenvolvimento de programas de computador"
}

## 🤝 Contribuição

Contribuições são bem-vindas!
Abra uma Issue para sugestões e envie um Pull Request para melhorias.

## 📜 Licença

Este projeto está sob a licença MIT.

