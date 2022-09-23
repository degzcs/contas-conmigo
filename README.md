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
After your commit the changes in the feature branch, do this:

```
git checkout deploy-pages
git merge <feature> --squash
git commit -m '<message>'
npm run build
git add dist && git commit -m '<message>'
git subtree push --prefix dist origin gh-pages
```
