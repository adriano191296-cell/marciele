# Publicar no GitHub (passo a passo)

Este projeto não está em um repositório git ainda (não existe pasta `.git`). Para publicar no GitHub:

## 1) Criar repositório local
No terminal, execute:

```bash
cd c:\Users\Adriano\12
git init
```

## 2) Adicionar arquivos
```bash
git add index.html TODO.md
```

(Se tiver outras pastas/arquivos do site, adicione também, por exemplo `imagem/`)

```bash
git add imagem
```

## 3) Fazer commit
```bash
git commit -m "Atualizações no site (imagens + fontes + scroll)"
```

## 4) Criar repositório no GitHub
Crie um repositório vazio no GitHub (ex: `meu-site`).

## 5) Conectar o remoto
Copie a URL do repositório (HTTPS) e execute:

```bash
git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
```

## 6) Subir para o GitHub
```bash
git branch -M main
git push -u origin main
```

---

Se você quiser, me diga:
- seu usuário no GitHub
- o nome do repositório
- se prefere HTTPS ou SSH

que eu te passo os comandos exatos.

