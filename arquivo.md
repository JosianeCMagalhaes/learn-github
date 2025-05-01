

```
# 📖 Guia Rápido de Comandos Git

Uma coletânea de comandos essenciais para quem está começando
ou quer relembrar os principais comandos do Git no dia a dia.

---

## 📌 Clonando um repositório

```bash
# Clona o repositório para sua máquina local
git clone https://github.com/usuario/repositorio.git
```

---

## 📌 Verificando o status do repositório

```bash
# Mostra os arquivos modificados, adicionados ou pendentes de commit
git status
```

---

## 📌 Adicionando arquivos para staging

```bash
# Adiciona todos os arquivos modificados para o staging
git add .

# Ou adicione arquivos específicos
git add nome-do-arquivo.extensao
```

---

## 📌 Realizando um commit

```bash
# Cria um commit com uma mensagem descritiva
git commit -m "Mensagem do commit"
```

---

## 📌 Enviando alterações para o repositório remoto

```bash
# Envia os commits da branch atual para o repositório remoto
git push origin main
```

---

## 📌 Trabalhando com branches

```bash
# Cria e troca para uma nova branch
git checkout -b nome-da-branch

# Troca para uma branch existente
git checkout nome-da-branch
```

---

## 📌 Atualizando seu repositório local

```bash
# Puxa as últimas alterações da branch main do remoto
git pull origin main
```

---

## 📌 Visualizando o histórico de commits

```bash
# Exibe o histórico de commits de forma resumida e em gráfico
git log --oneline --graph --all
```

---

## ✅ Dicas Extras

- Use `git status` antes de qualquer ação para saber o estado atual do seu repositório.
- Commits devem ter mensagens claras e descritivas.
- Sempre atualize sua branch local com `git pull` antes de iniciar alterações para evitar conflitos.
- Use branches para novas features, correções e ajustes.

---

> 📌 **Autor:** Josiane Magalhães  
> 📅 **Última atualização:** Abril/2025
```
