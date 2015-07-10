composer create-project --stability=beta magento/project-community-edition .
# create .gitignore from https://gist.github.com/gordonknoppe/3021964fb139e22d3453 - not using file provided by composer create-project
git init
git add composer.json
git add composer.lock
git add .gitignore
git commit -m 'initialize m2 composer project'

git clean -fxd
composer install

