## About

How to run Laravel on your Browser with [Browser PHP](https://github.com/capsulescodes/browser-php).

<br>
<br>

> [!NOTE]
> Access the CodeSandbox demo via this link : [CodeSandbox Demo](https://codesandbox.io/p/devbox/github/capsulescodes/articles/tree/012-run-laravel-on-your-browser-with-browser-php)

<br>

## Installation

0. Checkout branch

```bash
git checkout 012-run-laravel-on-your-browser-with-browser-php
```

<br>

1. Install dependencies

```bash
npm install

npm run composer install -- --ignore-platform-reqs --no-scripts
```

<br>

2. Copy Environment and generate app key

```bash
cp .env.example .env

npm run php artisan key:generate
```

<br>

3. Run development server script

```bash
npm run serve
```

<br>

5. Visit your website : http://localhost:2200
