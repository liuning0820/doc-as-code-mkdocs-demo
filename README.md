# doc-as-code-mkdocs-demo
static content generator by mkdocs and hosted on readthedocs.org

## add submodule

link and refer to another repo as the submodule for this repo

```
sudo git submodule add https://github.com/liuning0820/all-posts.git docs/all-posts

```

## update-git-submodule-to-latest-commit-on-origin-master

```sh
# Change to the submodule directory
cd submodule_dir

# Checkout desired branch
git checkout master

# Update
git pull

# Get back to your project root
cd ..

# Now the submodules are in the state you want, so
git commit -am "Pulled down update to submodule_dir"


# Or, if you're a busy person:

git submodule foreach git pull origin master


```
