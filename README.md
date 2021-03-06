# Symfony3ApiRestExample

[![Build Status](https://travis-ci.org/Tony133/Symfony3ApiRestExample.svg?branch=master)](https://travis-ci.org/Tony133/Symfony3ApiRestExample)

Example Symfony Api Rest with User Authentication HTTP Basic 

## Install with Composer

```
    $ curl -s http://getcomposer.org/installer | php
    $ php composer.phar install or composer install
```

## Getting with Curl 

```
    $ curl -H 'content-type: application/json' -v -X GET http://127.0.0.1:8000/api/books 
    $ curl -H 'content-type: application/json' -v -X GET http://127.0.0.1:8000/api/books/:id
    $ curl -H 'content-type: application/json' -v -X POST -d '{"name":"Foo bar","price":"19.99"}' http://127.0.0.1:8000/api/books 
    $ curl -H 'content-type: application/json' -v -X PUT -d '{"name":"Foo bar","price":"19.99"}' http://127.0.0.1:8000/api/books/:id
    $ curl -H 'content-type: application/json' -v -X DELETE http://127.0.0.1:8000/api/books/:id
```

## User Authentication with Curl 

```
    $ curl -H 'content-type: application/json' -v -X GET http://127.0.0.1:8000/api/books  -H 'Authorization:Basic username:password or email:password' 
```
