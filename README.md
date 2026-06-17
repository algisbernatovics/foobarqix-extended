# FooBarQix Extended

A PHP kata implementation of extended FooBarQix transformation rules with layered services, validation, and tests.

## Learning Goal

Practice taking a kata beyond a single file by separating input validation, transformation rules, controllers, services, and tests.

## Context

This kata is based on the extended FooBarQix exercise from the Craft Your Skills material. The step files in this repo document the progression through the exercise.

## Features

- Implements multiple transformation rules through service classes.
- Validates user input and handles domain exceptions.
- Includes step-by-step kata documentation files.
- Provides PHPUnit test coverage and a coverage screenshot.

## Tech Stack

- PHP
- Composer
- PHPUnit
- Object-oriented design

## Run

```bash
composer install
vendor/bin/phpunit
php public/index.php
```

## Project Structure

- `app/Services/` - transformation services
- `app/Validators/` - input validation
- `app/Controllers/` - application flow
- `tests/` - unit tests
- `step_*.md` - kata progression notes
- `coverage.png` - test coverage screenshot

## License

MIT License. See [LICENSE](./LICENSE). The kata prompt belongs to its original authors.
