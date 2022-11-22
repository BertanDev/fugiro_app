# Fugiro App

Este projeto foi desenvolvido como projeto integrador na faculdade de ADS!

Foi proposto que criássemos um sistema que fizesse a interação com sensores(Luminosidade, Nível de Água, Sonar e Temperatura) fictícios,
a aplicação deveria poder ler os dados(por entrada do usuário), armazena-lôs,
e serem disponibilizados para consulta.

Todo o sistema de Autenticação e armazenamento de informações foi feito com Firebase.

## A aplicação possui dois tipos de usuário:
- Usuário Comum: usuários do sistema(clientes)
- Usuário Master: administradores do sistema

## ▶ Testar o projeto

Com o projeto em sua máquina, rode na raiz:

```
npm install
```
Logo em seguida:
```
npm start
```

## ✔ Funcionalidades:
### Usuário Comum:
- Realizar Login.
- Atualizar e Vizualizar os valores dos seus sensores.
- Fazer logout da aplicação.

### Usuário Master:
- Realizar Login.
- Visualizar a lista de usuários.
- Excluir um usuário.
- Cadastrar um novo usuário.
- Vizualizar, excluir ou adicionar sensores no qual um usuário comum tem acesso e ver seus respectivos valores.
- Fazer logout da aplicação.

## 🛠 Ferramentas utilizadas:
- React JS
- JavaScript
- Banco de dados Firebase
- Context API
- React-toastify
- React-icons
- IBGE api
- React-router-dom

## 📸 Imagens da aplicação

### Página inicial, tela de login
![login](https://user-images.githubusercontent.com/72395637/203190400-f7173c8c-592f-4582-9057-0904c0f79845.JPG)

### Dashboard(usuário comum)
![tl1c](https://user-images.githubusercontent.com/72395637/203190806-cf1dd126-b4b7-46d3-98ba-a973ec4303a2.JPG)

### Dashboard(usuário master)
![tl1m](https://user-images.githubusercontent.com/72395637/203191235-0158b4dd-a2b4-4488-b56b-18ca68127e63.JPG)

### Tela de cadastro de novo usuário
![tl2m](https://user-images.githubusercontent.com/72395637/203191586-d1737c37-a226-454b-8955-47ce6d3ff456.JPG)

![tl3m](https://user-images.githubusercontent.com/72395637/203191588-6b3e2236-d6ef-41ba-95f8-0653e50fe5e2.JPG)

### Visualização dos sensores disponíveis em uma fazenda
![tl4m](https://user-images.githubusercontent.com/72395637/203192911-180a148a-8b90-414a-b640-e72622cd2959.JPG)

![tl5m](https://user-images.githubusercontent.com/72395637/203193121-097ae677-1efd-458a-964d-02602c23adb6.JPG)

