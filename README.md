# LABORATORY-SUBMODULE


Adding a submodule
```bash
$ git submodule add https://github.com/justalk/LABORATORY-SUBMODULE-INTERN lsi
```

If I click on the red folder I will be redirected to my other repository
![./documentation/1.png](./documentation/1.png)


If my submodule has a change, I need to go in the directory for pull the change.

I can make modification in the lsi folder as if it was a normal repository.


You can run git command on every submodule by using the `foreach` commands:

```bash
$ git submodule foreach 'git pull'
```