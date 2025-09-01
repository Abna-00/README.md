# README.md
Orientações do Projeto
# Gerenciador de Séries

Uma aplicação React para gerenciar sua coleção de séries favoritas.

## Funcionalidades

- ✅ Adicionar novas séries com formulário validado
- ✅ Visualizar todas as séries em uma lista
- ✅ Buscar séries por título, diretor ou categoria
- ✅ Editar informações das séries
- ✅ Excluir séries
- ✅ Interface responsiva

##  Tecnologias Utilizadas

- React.js
- React Router DOM
- CSS3
- HTML5

##  Instalação

1. No VS Code, abra a pasta onde foi salva o projeto. Ou use o comando 
Cd "exemplo\series-manager\src" no terminal do computador.

2. Instale as dependências:
npm install

3. Execute o projeto:
npm start

4. Será aberto automaticamente o projeto em http://localhost:3000 no navegador
5. Esse é o resultado esperado <img width="1919" height="911" alt="image" src="https://github.com/user-attachments/assets/b8e8aa41-f0fa-4a90-a28d-94cf7f9804fe" />

6. Estrutura do Projeto:
src/
  components/
    NavBar/          # Componente de navegação
    SerieList/       # Lista de séries
    SerieForm/       # Formulário de cadastro
  pages/
    Home.js          # Página inicial
    About.js         # Página sobre
   <img width="1919" height="909" alt="image" src="https://github.com/user-attachments/assets/3e594fdb-7faf-48c6-8ff7-70adc0cd1d34" />


  Register.js      # Página de cadastro
  <img width="1897" height="908" alt="image" src="https://github.com/user-attachments/assets/b8c729c2-dcf2-42d2-9503-484139d89359" />

  List.js          # Página de listagem
  <img width="1919" height="909" alt="image" src="https://github.com/user-attachments/assets/4ab2a90f-f3d3-4982-9443-ed6d41c9eae8" />

  App.js             # Componente principal
  data.js            # Dados iniciais

8. Como usar:
- Na página inicial, clique em "Cadastrar" para adicionar uma nova série

- Preencha todos os campos obrigatórios do formulário

- Clique em "Adicionar" para salvar a série

- Visualize todas as séries na página "Listar"

- Use a barra de busca para filtrar séries

- Clique em "Editar" para modificar uma série existente

- Clique em "Excluir" para remover uma série
