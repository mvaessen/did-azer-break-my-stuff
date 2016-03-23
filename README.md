# did-azer-break-my-stuff
A node utility to check if you are consuming a dependency affected by https://medium.com/@azerbike/i-ve-just-liberated-my-modules-9045c06be67c

## How to use

Install this globally:

```bash
$ npm install -g did-azer-break-my-stuff
```

Go to the repository you want to check:

```bash
$ cd my_repo && did-azer-break-my-stuff
```

If you are affected, it will output the list of affected packages and will return an error 1.
