# Anotações de Estudos sobre Git e GitHub

## Git

### O que é Git?

Git é um sistema de controle de versão distribuído que rastreia as alterações no código-fonte durante o desenvolvimento de software.

### Principais Comandos Git

- `git init`: Inicia um novo repositório Git.
- `git clone <URL>`: Clona um repositório existente para o diretório local.
- `git add <arquivo>`: Adiciona um arquivo ao index (staging area) para prepará-lo para o commit.
- `git commit -m "mensagem"`: Registra as alterações no repositório com uma mensagem descritiva.
- `git status`: Exibe o status atual do repositório.
- `git pull`: Atualiza o repositório local com as alterações do repositório remoto.
- `git push`: Envia as alterações locais para o repositório remoto.

### Branching

- `git branch`: Lista todas as branches no repositório.
- `git branch <nome>`: Cria uma nova branch.
- `git checkout <branch>`: Muda para a branch especificada.
- `git merge <branch>`: Incorpora as alterações de uma branch em outra.

### Resolução de Conflitos

- Durante o merge, podem ocorrer conflitos que precisam ser resolvidos manualmente.

## GitHub

### O que é GitHub?

GitHub é uma plataforma de hospedagem para projetos que utilizam o controle de versão Git.

### Colaboração

- **Fork:** Cria uma cópia pessoal de um repositório.
- **Pull Request (PR):** Solicita a incorporação de alterações de uma branch em um repositório.

### Issues

- Utilizadas para rastrear tarefas, melhorias ou bugs no projeto.

### Markdown no GitHub

- O GitHub utiliza a sintaxe Markdown para formatação em documentos e README.

## Dicas Gerais

- **.gitignore:** Utilize um arquivo .gitignore para ignorar arquivos e diretórios específicos.
- **git log:** Visualize o histórico de commits.
- **git remote:** Gerencie repositórios remotos.

Essas são anotações básicas. Para um entendimento mais profundo, consulte a documentação oficial do Git e GitHub.
