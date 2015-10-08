# testlib-skeleton

1. Get composer from: https://getcomposer.org/download/
 ```
 curl -sS https://getcomposer.org/installer | php
 ```
2. Get composer skeleton
 ```
 curl https://raw.githubusercontent.com/dafik/testlib-skeleton/master/composer.json > composer.json
 ```
3. Install dependencies
 ```
 ./composer.phar install
 ```

4. Run test (default visit localhost)
 ```
 ./bin/phpunit
 ```
