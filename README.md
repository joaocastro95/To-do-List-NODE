# 📰 To do List - NODE

O ***To do list*** é um projeto desenvolvido sobre orientação de Node.js e organização estrutual MVC em JavaScript durante o curso oferecido pela Hora de Codar. Ele permite que os usuários adicionem, removam e marquem tarefas como concluídas, proporcionando uma interface interativa e dinâmica. O código implementa uma lógica para gerenciar as tarefas, garantindo que a interface seja atualizada automaticamente conforme o usuário interage com a aplicação.


## 🌐 Interface Web

A página principal apresenta uma interface simples e funcional, permitindo ao usuário realizar operações matemáticas básicas de forma intuitiva.

![Página Principal](/img/print1.png)


### 🔍 Testando Localmente

Para testar o projeto localmente, siga estas etapas:

1. Abra o terminal (ou prompt de comando) e execute o seguinte comando para clonar o repositório:

   `git clone https://github.com/joaocastro95/To-do-List-NODE.git`

2. Após clonar o repositório, abra o terminal e vá até a pasta clonada.
   
   `cd caminho/para/a/pasta/do/projeto`

3. Instale as dependências.

  `npm install`
   
4. Inicialize o projeto.

   `npm start`

5. Abra a porta no navegador.

   `http://localhost:3000/tasks`

Isso abrirá a interface web do projeto. Se o servidor estiver funcionando corretamente, você verá a página principal onde poderá utilizar o "To do list - NODE".


#### 📝 Observação
Se você encontrar algum problema ou a página não carregar, consulte a seção de [Autores](#-autores) e entre em contato conosco.


## 🛠️ Estrutura do Projeto
Mantivemos uma estrutura organizada para facilitar a manutenção e a compreensão do código:

# 📝 To-Do List com Node.js

Projeto de lista de tarefas com backend em Node.js, Express, Handlebars e frontend básico.

## 🚀 Estrutura do Projeto

### **Backend**
- **`controllers/`**  
  - `TaskController.js`: Lógica do CRUD (criar, ler, atualizar, deletar tarefas).  
- **`db/`**  
  - `conn.js`: Configuração da conexão com o banco de dados (ex: MongoDB).  
- **`models/`**  
  - `Task.js`: Modelo de dados das tarefas.  
- **`routes/`**  
  - `tasksRoutes.js`: Rotas da API para gerenciar tarefas.  
- **`views/`**  
  - **`layouts/`**  
    - `main.handlebars`: Template base do Handlebars.  
  - **`tasks/`**  
    - `all.handlebars`: Página que lista todas as tarefas.  
    - `create.handlebars`: Formulário de criação de tarefas.  
    - `edit.handlebars`: Formulário de edição de tarefas.  
- **`index.js`**: Arquivo principal do servidor (configura Express, Handlebars, etc.).  

### **Frontend**
- **`public/css/`**  
  - `styles.css`: Estilos CSS das páginas.  

### **Configurações**
- **`.gitignore`**: Ignora arquivos como `node_modules` e `.env`.  
- **`package.json`**: Lista de dependências e scripts.  
- **`package-lock.json`**: Versões exatas das dependências.  
- **`README.md`** - Documentação do projeto.

  ---
## 🚀 Tecnologias Utilizadas

| Ferramenta       | Descrição                                         |
| ---------------- | ------------------------------------------------- |
| ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) | Ambiente de execução JavaScript backend |
| ![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white) | Framework para construção do servidor web |
| ![Handlebars](https://img.shields.io/badge/Handlebars.js-f0772b?style=for-the-badge&logo=handlebarsdotjs&logoColor=black) | Engine de templates para renderização HTML |
| ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) | Banco de dados relacional utilizado |
| ![MySQL Workbench](https://img.shields.io/badge/MySQL_Workbench-4479A1?style=for-the-badge&logo=mysql&logoColor=white) | Interface gráfica para gerenciamento do banco |
| ![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white) | ORM para conexão com MySQL |
| ![HTML5/CSS3](https://img.shields.io/badge/HTML5%20/%20CSS3-E34F26?style=for-the-badge&logo=html5&logoColor=white) | Estrutura e estilização das páginas |
| ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white) | Editor de código utilizado |
| ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white) | Sistema operacional utilizado |

## 📝 Autores

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/132524175?v=4" width=115><br><sub>João Castro</sub>](https://github.com/joaocastro95) |
| --- |
