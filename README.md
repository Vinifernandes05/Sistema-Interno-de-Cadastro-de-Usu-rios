# Sistema Interno de Cadastro de Usuários
Este projeto consiste em um sistema interno de cadastro de usuários desenvolvido em JavaScript (Node.js). O sistema permite cadastrar, listar, editar e excluir usuários, armazenando os dados em um arquivo JSON local. O endereço do usuário (Rua, Bairro, Cidade e Estado) é preenchido automaticamente a partir do CEP informado, utilizando a API pública "ViaCEP".

## Tecnologias Utilizadas

- JavaScript (Node.js)
- Módulo nativo `fs` (File System)
- API pública ViaCEP
- JSON para persistência de dados

## Estrutura do Projeto

```
Sistema-Interno-de-Cadastro-de-Usuarios/
│
├── Campos_usuarios.js
├── Validar_usuarios.js
├── Dados_usuarios.json
└── README.md
```

## Como Executar o Projeto

1. Clone o repositório:
   git clone <link-do-repositorio>

2. Acesse a pasta do projeto:
   cd Sistema-Interno-de-Cadastro-de-Usuarios

3. Execute o sistema:
   Abra o terminal e digite "node Campos_usuarios.js"

## API Utilizada

O projeto utiliza a API pública "ViaCEP" para consultar automaticamente os dados de endereço a partir do CEP informado.
Documentação: https://viacep.com.br
   
