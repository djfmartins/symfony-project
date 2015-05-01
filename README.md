# symfony-project
CentOS VM with empty Symfony project


## How to use


####1) Checkout the project in your workdir
```
git clone git@github.com:djfmartins/symfony-project.git
```

####2) Install dependencies
```
composer install
```

####3) Add `http://symfony-project.dev/` to the hosts (optional)
In order to access the project in your browser through the url `http://symfony-project.dev/`,
add the following line to your hosts file (`/etc/hosts`)

```
192.168.56.103 symfony-project.dev
```

####4) Access your project
Visit the page `http://symfony-project.dev/config.php` to check your configuration

Access the dev page at `http://symfony-project.dev/app_dev.php`
