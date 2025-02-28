# Kanban Pessoal - Edição Baseada em Arquivos

Uma aplicação de quadro Kanban bonita, intuitiva e rica em recursos para gerenciamento de tarefas.

## ✨ Recursos Principais

- ✅ **Gerenciamento de Tarefas** com suporte a arrastar e soltar
- 🛠 **Múltiplas Colunas**: A Fazer, Em Progresso, Concluído
- 📅 **Detalhamento Completo**: prioridade, datas de vencimento e descrição
- 💡 **Modo Claro/Escuro** com cores adaptáveis
- 📊 **Painel de Estatísticas** sobre tarefas e produtividade
- 🌐 **Design Responsivo** para todos os dispositivos

---

## 🔍 Requisitos

Antes de iniciar, certifique-se de ter instalado:

- **Node.js** (v14 ou superior)
- **npm** ou **yarn**

---

## 🚀 Como Começar

1. Clone este repositório:
   ```sh
   git clone https://github.com/RxTaylin/Personal-Kanban.git
   cd kanban-pessoal
   ```
2. Instale as dependências:
   ```sh
   npm install  # ou yarn install
   ```
3. Inicie a aplicação:
   ```sh
   npm start  # ou yarn start
   ```
4. Acesse no navegador:
   ```
   http://localhost:
   ```

---

## 🌟 Como Usar

### 🗒️ Visualização do Quadro

- Clique em qualquer coluna para **criar uma nova tarefa**
- Arraste e solte tarefas entre colunas para **atualizar o status**
- Clique em uma tarefa para **editar seus detalhes**
- As tarefas são **salvas automaticamente** no localStorage do navegador

### 📊 Visualização do Painel

- **Estatísticas detalhadas** sobre suas tarefas
- **Distribuição por status e prioridade**
- **Gráficos de progresso** ao longo do tempo
- **Tempo médio de conclusão** de tarefas

---

## 📚 Detalhes Técnicos

- **Frontend:** React com TypeScript
- **Gerenciamento de Estado:** React Hooks
- **Arrastar e Soltar:** dnd-kit
- **Estilização:** Tailwind CSS
- **Gráficos:** Recharts
- **Armazenamento:** localStorage do navegador

---

## 📂 Persistência de Dados

As tarefas são armazenadas **localmente no seu navegador** via localStorage.

---

## 🛡️ Solução de Problemas

Caso encontre problemas, tente as soluções abaixo:

1. **Verifique se seu navegador suporta localStorage**
2. **Confirme se há espaço suficiente** para salvar os dados
3. **Se as tarefas sumirem após reiniciar**, tente **importar um quadro salvo**
4. **Se houver comportamentos inesperados**, limpe o cache do navegador

---

## 👨‍💻 Contribuição

Contribuições são bem-vindas! Para sugerir melhorias:

1. **Fork este repositório**
2. **Crie uma branch** (`feature/nova-funcionalidade`)
3. **Faça um commit** das suas mudanças
4. **Abra um Pull Request**

---

🎉 **Divirta-se organizando suas tarefas com o Kanban Pessoal!**