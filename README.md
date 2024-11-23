# 🎵 Catálogo de Discos Musicais 🎸

Este projeto é uma aplicação desenvolvida utilizando o padrão **MVC (Model-View-Controller)** para gerenciar um catálogo de discos musicais. O sistema permite cadastrar, editar, buscar e remover informações sobre discos, artistas e gêneros musicais. Ele é ideal para colecionadores ou entusiastas da música que desejam organizar e visualizar suas coleções de forma eficiente.

---
## Imagem da Pagina Inicial do Projeto
![image](https://github.com/user-attachments/assets/da67d136-e54a-4940-8b78-952fc4bb9fa3)
## 🛠️ Funcionalidades

1. **Gerenciamento de Discos**
   - Cadastro de discos, incluindo título, ano de lançamento, capa (imagem) e lista de faixas.
   - Visualização da lista de discos com informações detalhadas: artista, ano de lançamento e faixas.
   - Edição e exclusão de discos.

2. **Gerenciamento de Artistas**
   - Cadastro de artistas com nome, gênero musical e associação a discos existentes.
   - Visualização de artistas cadastrados e os discos em que participaram.
   - Edição e exclusão de artistas.

3. **Gerenciamento de Gêneros Musicais**
   - Associação de discos, artistas e faixas a um ou mais gêneros musicais.
   - Visualização de gêneros e suas associações.
   - Edição e exclusão de gêneros.

4. **Busca Avançada**
   - Busca de discos, artistas e faixas com filtros por:
     - Título.
     - Artista.
     - Gênero musical.

---

## 📂 Estrutura do Projeto

- **Model:** Contém as regras de negócios e acesso ao banco de dados para discos, artistas e gêneros.
- **View:** Interface gráfica simples e intuitiva para interação do usuário.
- **Controller:** Gerencia a lógica de fluxo entre Model e View, processando as requisições do usuário.

---

## 📋 Requisitos do Sistema

### Dados a Gerenciar

- **Discos:** Título, ano de lançamento, capa (imagem) e lista de faixas.
- **Artistas:** Nome, gênero musical e lista de discos associados.
- **Gêneros Musicais:** Associação a discos, artistas e faixas.

### Funcionalidades

- Cadastro, edição e remoção de discos, artistas e gêneros.
- Listagem de discos com detalhes (artista, ano de lançamento e faixas).
- Busca com filtros por título, artista e gênero musical.

---

## 🔧 Tecnologias Utilizadas

- **Backend:** Node.js
- **Banco de Dados:** PostgreSQL
- **Frontend:** HTML, CSS, e JavaScript.
- **Gerenciamento de Dependências:** npm

---

## 🚀 Como Executar

### 1. Configuração do Banco de Dados
---
Clone o repositório:
``` bash
git clone https://github.com/Daigder/Projeto-Catalogo-musical-MVC.git
```
Instale as dependências:
``` bash
npm install
```


Configure o Banco de Dados:
```bash
CREATE DATABASE MusicProject;
```
Execute as migrações e seeds para popular o banco de dados:
```bash
npx sequelize db:migrate
```
Inicie o servidor:

```bash
npm start
```
Acesse a aplicação no navegador:
- Acesse o endereço http://localhost:3000.

## 🖥️ Telas da Aplicação

1. **Página Inicial**
   - Tela principal que apresenta um resumo do sistema e atalhos para as principais funcionalidades.

2. **Página De Disco**
   - Permite o cadastro de novos discos
    informando título, ano de lançamento, capa (imagem) e faixas.

3. **Página De Artista**
   - Permite o cadastro de novos artistas com nome, gênero musical e associação a álbuns já cadastrados.

4. **Página De Gênero**
   - Exibe os registros cadastrados de gêneros.

5. **Página Buscar Álbuns e Artistas**
   - Oferece filtros dinâmicos para localizar álbuns e artistas por título, nome ou gênero musical.

6. **Página Ver Lista de Álbuns**
   - Apresenta uma lista completa de álbuns cadastrados com detalhes como título, ano de lançamento, capa, faixas e artista associado.


## 👨‍💻 Desenvolvedor
<table>
  <tr>
    <td style="text-align: center;">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/125320205?v=4" width="150px;" alt="Murillo Daigder"/>
        <br>
        <sub><b>Murillo Daigder</b></sub>
      </a>
    </td>
<table>

## 📌 Considerações Finais
Este projeto tem como objetivo não apenas organizar informações sobre discos, mas também oferecer uma experiência amigável ao usuário. Desenvolvido com uma arquitetura escalável e tecnologias modernas, o sistema pode ser facilmente ampliado para incluir outras funcionalidades no futuro.
