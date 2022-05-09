very simple and self-explanatory repository.

run app.js which imports value from test-package and prints it.
```
pnpm start
```

very important: I wasted about 3 hours because of it: 
your `app` package must state that it depends on `test-package` package, and you should add `prefer-workspace-packages=false` option to your `.npmrc` file. 
