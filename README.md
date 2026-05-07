# Atividade06.01

O Git e o GitHub são ferramentas relacionadas, mas com papéis diferentes:

Git é um sistema de controle de versão.
GitHub é uma plataforma online que hospeda repositórios Git e facilita colaboração.
Principais funções do Git

O Git serve para controlar o histórico de alterações do código e permitir trabalho em equipe sem sobrescrever o trabalho dos outros.

Funções principais:
Controle de versão: salva o histórico de todas as mudanças no projeto.
Restauração: permite voltar para versões anteriores do código.
Trabalho em equipe: vários desenvolvedores podem trabalhar no mesmo projeto.
Ramificações (branches): cria linhas paralelas de desenvolvimento.
Fusão (merge): junta mudanças de diferentes branches.
Principais comandos do Git
Inicialização e configuração
git init → cria um repositório Git local
git config → configura usuário e e-mail
Controle de alterações
git status → mostra o estado dos arquivos
git add . → adiciona arquivos para commit
git commit -m "mensagem" → salva alterações no histórico
Histórico e versões
git log → mostra histórico de commits
git diff → mostra diferenças entre versões
Trabalho com repositórios remotos
git clone URL → copia um repositório remoto
git remote add origin URL → conecta ao GitHub
git push → envia alterações para o GitHub
git pull → baixa alterações do GitHub
Branches
git branch → lista branches
git branch nome → cria branch
git checkout nome → muda de branch
git merge nome → junta branches
Principais funções do GitHub

O GitHub funciona como uma “rede social de código” e uma plataforma de hospedagem de repositórios.

Recursos principais:
Hospedagem de código na nuvem
Colaboração em projetos
Pull requests (revisão de código antes de aceitar mudanças)
Issues (rastreamento de problemas e tarefas)
GitHub Actions (automação de testes e deploy)
GitHub Pages (publicação de sites estáticos)

GitHub Official Website

 Passos para colocar seu projeto online no GitHub
1. Criar repositório no GitHub
Acesse o GitHub
Clique em “New repository”
Dê um nome ao projeto
2. Inicializar o Git no projeto local
git init
3. Adicionar arquivos
git add .
4. Criar commit
git commit -m "primeiro commit"
5. Conectar ao GitHub
git remote add origin https://github.com/seu-usuario/seu-repo.git
6. Enviar o projeto
git push -u origin main
Publicar site online (opcional: GitHub Pages)

Se for um site (HTML, CSS, JS), você pode usar o GitHub Pages:

Vá em Settings > Pages
Escolha a branch (main ou gh-pages)
O GitHub gera um link público automaticamente
