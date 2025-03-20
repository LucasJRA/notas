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

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
