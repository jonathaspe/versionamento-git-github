# DIO | Resumo de Git e GitHub

Repositório para armazenar resumos sobre o Git e o GitHub do Curso de Versionamento de Código com Git e GitHub da  [Digital Innovation One](https://web.dio.me/home).

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/pt)

## 👨‍💻 Resumo das aulas

| Aulas | Resumos |
| Testes de Escrita | README.md |
| Testes de Escrita | Dentro de uma tabela |

### 🖥️ Simulando código de computador
```
// Comandos da linha de comando
mkdir [Nome da Pasta]
touch [Nome da Pasta/Nome do Arquivo.md]

// Principais comandos do git
git init
git clone [URL do repositório desejado]
git clone [URL do repositório desejado] --branch [Nome do Repositório] --single-branch
git log
git restore [Nome do Arquivo]
git commit --amend -m "Novo texto desejado"
git push
git reflog
git pull
git stash (arquivar as alterações realizadas localmente)
git stash list
git stash pop
git stash apply

// Comandos para excluir alterações realizadas em um arquivo
git reset [código do Commit desejado]
git reset [Nome do Arquivo] ou [Nome da Pasta/Nome do Arquivo.md]
git reset --soft [código do Commit desejado]
git reset --hard [código do Commit desejado]


// Comandos para a criação, pesquisa, exclusão e mescla de branch
git checkout -b [Nome da Brach]
git checkout [Nome da Brach desejada]
git branch -v (para visualizar o último commit de cada branch)
git merge [Nome da Brach que deseja mesclar com a branch atual]
git branch
git branch -d [Nome da Brach que deseja excluir]

// Resolução de conflitos
git fetch origin main
git diff
git diff main origin/main
git merge origin/main

```

## Referências

