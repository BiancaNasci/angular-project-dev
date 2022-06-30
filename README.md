## 👑 Principais comandos do GIT 👑

### Defini o nome de usuário

```bash
git config --global user.name “BiancaNasci”
```

### Defini o email do usuário

```bash
git config --global user.email “bianascig@gmail.com”
```

### Inicializa o repositório

```bash
git init
```

### Verifica se houve alterações / estado dos arquivos

```bash
git status
```

### Coloca o arquivo em Staging

```bash
git add NomeDoArquivo.txt
```

### Realiza o Commit

```bash
git commit -m "meu commit aqui"
```

### Informar a pasta remota (Via HTTPS):

(lembre-se de trocar o usuário no comando)

```bash
git remote add origin https://github.com/adosilva/senai-versoes-colaboracoes.git
```

### Informar a pasta remota (Via SSH):

(lembre-se de trocar o usuário no comando)

```bash
git remote add origin git@github.com:adosilva/senai-versoes-colaboracoes.git
```

### Visualizar o repositório remoto:

```bash
git remote –v
```

### Alterar o nome da branch principal de Master para Main (isso é uma boa prática atualmente recomendada)

```bash
git branch -M "main"
```

### Realiza o envio dos commits para o branch master

```bash
git push origin master
```

### Baixar a alteração feita no repositório remoto:

```bash
git pull
```

### Cria uma tag

```bash
git tag -a <nome da tag> -m <comentário>
```

### Realiza o envio das Tags para o repositório remoto

```bash
git push origin --tags
```

### Muda para a branch Master

```bash
git checkout master
```

### Cria uma nova branch

```bash
git checkout -b nome-branch
```

### Realiza o envio dos commits para a nova branch

```bash
git push origin nome-branch
```

### Faz a mesclagem com outra branch

```bash
git merge origin nome-branch
```

Observação:  git config --global --add safe.directory '%(prefix)///DSN4021233054/Dados/Desenv. Web MKT DIG/Alunos/Bianca Gonçalves/AULA35/angular-project-dev'
