# Projeto-Web_Gerenciamento-Tarefas

# **Aplicativo de Gerenciamento de Tarefas**

## **Descrição do Projeto**
O Aplicativo de Gerenciamento de Tarefas é uma solução web que permite aos usuários organizarem suas atividades de forma eficiente. O sistema oferece funcionalidades como criar, editar, excluir e priorizar tarefas, bem como notificações automáticas para manter os usuários atualizados sobre prazos e progresso.

---

## **Funcionalidades**
- **Criação de Tarefas**: Adicione novas tarefas com título, descrição e data de vencimento.
- **Edição de Tarefas**: Altere informações de tarefas existentes.
- **Exclusão de Tarefas**: Remova tarefas concluídas ou desnecessárias.
- **Prioridades**: Categorize as tarefas por nível de prioridade (Alta, Média, Baixa).
- **Notificações**: Alertas para tarefas pendentes e vencidas.
- **Responsividade**: Funciona em dispositivos móveis e desktop.

---

## **Arquitetura do Sistema**
- **Front-end**:  
  Tecnologias utilizadas:  
  - HTML, CSS, JavaScript, TypeScript.  
  Objetivo: Criar uma interface responsiva, intuitiva e acessível.

- **Back-end**:  
  Tecnologias utilizadas:  
  - C#, MySQL.  
  Objetivo: Fornecer uma API RESTful robusta para gerenciar os dados do aplicativo.

- **UI/UX Design**:  
  Ferramenta utilizada:  
  - Figma.  
  Objetivo: Desenvolver wireframes e protótipos funcionais e esteticamente agradáveis.

---

## **Tecnologias Utilizadas**
- **Front-end**:  
  - HTML5 e CSS3: Estrutura e estilo.  
  - JavaScript: Interatividade.  
  - TypeScript: Tipagem estática e melhor manutenção do código.

- **Back-end**:  
  - C#: Construção da API RESTful.  
  - MySQL: Armazenamento e consulta de dados.

- **UI/UX**:  
  - Figma: Criação de wireframes e protótipos.

- **Controle de Versão**:  
  - Git e GitHub.

---

## **Como Executar o Projeto**

### Pré-requisitos
Certifique-se de ter as seguintes ferramentas instaladas no seu sistema:  
- [Node.js](https://nodejs.org) e [npm](https://www.npmjs.com/): Para o front-end.  
- [Visual Studio](https://visualstudio.microsoft.com/): Para o desenvolvimento back-end.  
- [MySQL](https://www.mysql.com/): Para o banco de dados.  
- [Git](https://git-scm.com/): Para controle de versão.

### Passos
1. Clone este repositório:
   ```bash
   git clone https://github.com/usuario/repo-gerenciamento-tarefas.git
   ```
2. Instale as dependências do front-end:
   ```bash
   cd frontend
   npm install
   ```
3. Configure o banco de dados:
   - Crie um banco no MySQL chamado `task_manager`.
   - Execute o script de criação do banco localizado em `backend/db/schema.sql`.

4. Inicie o servidor back-end:
   ```bash
   cd backend
   dotnet run
   ```
5. Inicie o front-end:
   ```bash
   cd frontend
   npm start
   ```

6. Acesse o aplicativo no navegador:  
   - URL: `http://localhost:3000`

---

## **Contribuição**
Siga estas etapas para contribuir com o projeto:
1. Faça um fork do repositório.
2. Crie um branch para a sua funcionalidade: `git checkout -b minha-funcionalidade`.
3. Faça suas alterações e commit: `git commit -m "Minha contribuição"`.
4. Envie o branch: `git push origin minha-funcionalidade`.
5. Abra um Pull Request.

---

## **Testes**
- Utilize a ferramenta **Postman** para testar as rotas da API.
- Testes unitários são executados usando as bibliotecas integradas do framework utilizado no back-end.

---

## **Cronograma**
### Fases do Projeto
1. **Planejamento e Design**: 5 dias.
2. **Desenvolvimento Front-end**: 15 dias.
3. **Desenvolvimento Back-end**: 15 dias.
4. **Testes e Validação**: 5 dias.
5. **Entrega e Documentação**: 3 dias.

---

## **Licença**
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

---

## **Contato**
Para dúvidas ou sugestões, entre em contato:  
- **Email**: email@exemplo.com  
- **GitHub**: [seu_perfil](https://github.com/seu_perfil)
