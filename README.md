# contas-conmigo

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Deploy
After your commit the changes in your feature branch, do this:

```
git checkout deploy-pages
git merge <feature> --squash
git commit -m '<message>'
npm run build
git add dist && git commit -m '<message>'
git subtree push --prefix dist origin gh-pages
```
NOTE: the `deploy-pages` branch allows commit the changes in the `dist` folder
NOTE: in case that you have issues with  the remote `gh-pages` branch,
you can delete it and created again with the last deploy.
