# Test-PHP-Code-With-PHPUnit

### How to Run Tests in PHPUnit
You can run all the tests in a directory using the PHPUnit binary installed in your vendor folder.

```
$ ./vendor/bin/phpunit --verbose tests
```

You can also run a single test by providing the path to the test file.

```
$ ./vendor/bin/phpunit --verbose tests/UserTest.php
```

You use the --verbose flag to get more information on the test status.
