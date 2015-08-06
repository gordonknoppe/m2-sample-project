Commands used to initialize this repository

    composer create-project --stability=dev magento/project-community-edition .
    git add .
    git commit -m 'initialize m2 composer project'

Clean up and test a full composer install

    git clean -fxd
    composer install
