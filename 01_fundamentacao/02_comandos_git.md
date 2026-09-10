# Comandos Básicos de Git

## 1. Iniciar e Clonar
* `git init` — Inicializa um repositório na pasta atual
* `git clone [url]` — Baixa um repositório remoto

## 2. Fluxo de Trabalho Local
* `git status` — Mostra o estado dos arquivos
* `git add [arquivo]` — Adiciona o arquivo para a área de preparação (staging)
* `git add .` — Adiciona todas as alterações para staging
* `git commit -m "[mensagem]"` — Salva as alterações com uma mensagem

## 3. Branches (Ramos)
* `git branch` — Lista as branches do repositório
* `git branch [nome]` — Cria uma nova branch
* `git switch [nome]` ou `git checkout [nome]` — Alterna para uma branch
* `git merge [nome]` — Une a branch informada na branch atual

## 4. Sincronização Remota (GitHub)
* `git remote add origin [url]` — Conecta o repositório local ao GitHub
* `git push -u origin main` — Envia os commits locais para o servidor
* `git pull` — Baixa e atualiza o repositório com as novidades do servidor