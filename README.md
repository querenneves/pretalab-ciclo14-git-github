# 📚 Aulas de Git e GitHub  

Este repositório contém anotações práticas dos principais comandos de **Git e GitHub**, organizados de forma simples para consulta rápida durante os estudos.  

---

## 📑 Sumário  

- [🌿 Trabalhando com Branches](#-trabalhando-com-branches)  
- [📦 Stash (guardando alterações temporárias)](#-stash-guardando-alterações-temporárias)  
- [🏷️ Trabalhando com Tags](#️-trabalhando-com-tags)  
- [⚡ Criando Atalhos (Alias)](#-criando-atalhos-alias)  
- [✅ Resumindo](#-resumindo)  

---

## 🌿 Trabalhando com Branches  

Comandos para criar, listar e alternar entre branches:  

```bash
git branch                 # lista branches
git checkout -b feature    # cria e entra na branch 'feature'
git checkout feature       # entra na branch 'feature'
git checkout main          # volta para a branch 'main'
git merge feature          # mescla a 'feature' na 'main'

---

## 📦 Stash (guardando alterações temporárias)
O stash permite salvar alterações não commitadas sem perdê-las, liberando a área de trabalho:

git stash                  # guarda alterações não commitadas
git stash pop              # restaura e remove o último stash

---

## 🏷️ Trabalhando com Tags
Tags são rótulos que marcam commits específicos no histórico do projeto:

git tag v1.0                       # cria uma tag simples
git tag -a v2.0.0 -m "Versão estável"  # cria tag anotada com mensagem
git push origin v2.0.0             # publica a tag no remoto
git tag --list        # lista todas as tags

---

## ⚡ Criando Atalhos (Alias)         
Alias facilitam a digitação de comandos frequentes:

git config --global alias.st status     # cria atalho 'git st' para 'git status'
git config --global alias.co checkout   # cria atalho 'git co' para 'git checkout'

---

Exemplos de uso:

git st
git co main
git co feature-queren

---

## ✅ Resumindo
Este guia cobre:

🌿 Criação, listagem e troca de branches

📦 Uso de stash para salvar alterações temporárias

🏷️ Criação, listagem e publicação de tags

⚡ Definição de atalhos para agilizar comandos