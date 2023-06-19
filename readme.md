# inicializando git local

Primeiro confira se o git está instalado:

```bash
git --versions
```
Após verificar se está instalado você deve abrir a pasta documentos:

```bash
cd Documents/
```
Após isso verifique as pastas dentro de seus documentos

```bash
ls
```

Após isso você precisa configurar o git:

```bash
git config --global user.name "seunome"
```

```bash
git config --global user.email "seuemail"
```

Depois de configura-lo você precisa criar uma pasta para guardar seus documentos:

```bash
mkdir "nome da pasta"
```

Após isso você precisa verificar se sua pasta foi criada com sucesso:

```bash
ls
```

Após ver se sua pasta está lá criada você pode acessar ela:

```bash
cd notas/
```

após isso você deve criar um repositório para o seu git:

```bash
git init
```

Por fim abra seu vscode na pasta desejada:

```bash
code .
```

--------------------------------------
Códigos que vamos usar na próxima aula (pesquisar):


Git status = permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git.

```bash
git status
```

git add = git add adiciona uma alteração no diretório ativo à área de staging
```bash
git add <filename ou .>
```

git branch = permite criar, listar, renomear e excluir ramificações
```bash
git branch <branchname>
```

git checkout = é uma forma de alternar entre versões de arquivos, commits ou branches.
```bash
git checkout <branchname>
```
git chekout -b = uma sinalização de conveniência que diz ao Git para rodar o git branch antes de rodar o git checkout
```bash
git checkout -b <branchname>
```

git commit = são as unidades estruturais de um cronograma de projeto Git
```bash
git commit -m "<description>"
```

git push =  enviar conteúdo do repositório local para um repositório remoto
```bash
git push
```

Forçar a exclusão da ramificação especificada, mesmo que ela tenha mudanças não mescladas.
```bash
git branch -D <branchame>
```

git fetch = usado para baixar todos os commits do repositório remoto sem afetar o seu código local.
```bash
git fetch
```

git pull = é uma abreviação do comando git fetch
```bash
git pull
```