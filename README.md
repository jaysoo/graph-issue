Demo for issue with graph and building dependencies from `package.json`.

Run `npx nx graph` from this repo and you will see the `test -> test2` is marked as dynamic, whereas it was previously static. 

