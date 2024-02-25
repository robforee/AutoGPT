
# Sync upstream changes
* update my local and my fork
```
git fetch upstream
git checkout master
git merge upstream/master
git push origin master
```


# Foree contributions 

## git process for private mods
```
git checkout -b foree-features
```

* make some changes

```
git add .
git commit -m "Foree feature cahnges"
git push origin foree-features
```

## git process for contributions to orignal repo
* update local and form from origin
* create a branch for contribution
```
git checkout -b feature-contribution
```

* make changes, commit branch, push to my-fork
```
git add .
git commit -m "Feature contribution"
git push origin feature-contribution
```

* Go to GitHub (robforee/AutoGPT) 
* create a new pull request. 
** Select the base repository as Significant-Gravitas/AutoGPT and compare across forks to select your feature-contribution branch.

