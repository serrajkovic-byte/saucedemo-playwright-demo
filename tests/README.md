# SauceDemo Playwright Login Tests

## Overview

Automated UI login tests for the SauceDemo training website using Playwright
Test, JavaScript, and Node.js.

## Scope

Authentication only:

- Valid login
- Locked-out user
- Unknown user
- Wrong password
- Empty fields
- Password masking

## Installation

```bash
npm ci
npx playwright install chromium
```

## Run tests

```bash
npm test
npm run test:login
npm run test:headed
npm run report
```

## Architecture

- Tests: `tests/login.spec.js`
- Page Object: `tests/pages/LoginPage.js`
- Test data: `tests/data/testData.js`
