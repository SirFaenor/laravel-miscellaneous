Selective environment variables loading based on current host, useful for setting different configurations during development. 
Create a file for each execution host inside `/env` folder and insert custom or overloaded variables into them.

Eg.
```
env/.master.env
env/.my-awesome-host.tld.env
env/.my-local-development-host.env
```

Requires https://github.com/vlucas/phpdotenv.