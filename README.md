# Miscellaneous code and files for Laravel.
Collection of code used in some Laravel projects.  
Each `scr` subfolder emulates path of a default Laravel installation.

### [Deployment setup on shared hosting](deployment-shared-hosting)
Readme for deployment on shared hosting, if you cannot change default document root for a domain.

### [Htaccess in middleware](middleware-htaccess)
A middleware replacing some useful rules usually contained in `.htaccess` files.

### [Selective environment variables](selective-env-variables)
Selective environment variables loading based on current host, useful for setting different configurations during development.  
Requires https://github.com/vlucas/phpdotenv.
