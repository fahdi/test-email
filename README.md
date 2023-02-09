# Test Email Repository

This repository is for testing the `Email.php` class, with the help of `EmailTest.php` which uses PHPUnit for unit testing. The `Email.php` class contains three different methods that will be tested.

## Requirements

- PHP 7.2 or later
- PHPUnit 8.5 or later

## How to Run Tests

1. Clone the repository to your local machine:

```bash
git clone https://github.com/fahdi/test-email.git
```

1. Navigate to the repository directory:

```bash
cd test-email
```

1. Install dependencies using Composer:

```bash
composer install
```

1. Run PHPUnit to execute the tests:

```bash
vendor/bin/phpunit
```

##TestDox

Below you see an alternative output which is based on the idea that the name of a test can be used to document the behavior that is verified by the test:

```bash
./vendor/bin/phpunit --testdox tests
```
## Code of Conduct

Please refer to the [Code of Conduct](CODE_OF_CONDUCT.md) for guidelines on contributing to this repository.

## License

This repository is licensed under the [MIT License](LICENSE).
