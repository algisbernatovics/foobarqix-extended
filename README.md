# FooBarQix Extended

A PHP kata implementation of the FooBarQix transformation rules with layered services, validation, and tests.

## Overview

A PHP kata implementation of the FooBarQix transformation rules with layered services, validation, and tests.

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

## Project Structure

- `app/Services/` - transformation services
- `app/Validators/` - input validation
- `app/Controllers/` - application flow
- `tests/` - unit tests
- `step_*.md` - kata progression notes

## Getting Started

Install dependencies and run tests:

```bash
composer install
vendor/bin/phpunit
```

Run the public entry point:

```bash
php public/index.php
```

## Portfolio Notes

- Shows decomposition of a kata into services, validators, and tests.
- Good example of building beyond a single-file exercise.

## Status

Portfolio-ready PHP kata.
