### Welcome to my GitHub profile! 🎉

#### About me

Hi, I'm Emmie Block! 👋 I'm a software developer with a passion for building scalable and maintainable applications. In my free time, I enjoy learning about new technologies and exploring the world of coding.

#### Skills

* **Primary language:** TypeScript 💻
* **UI framework:** Tailwind 💃
* **Back-end framework:** Node.js 🚀
* **Query language:** GraphQL 🤔

#### Get in touch

If you're interested in collaborating or just want to say hi, feel free to reach out to me at [emmie.emmie@hotmail.com](mailto:emmie.emmie@hotmail.com)

#### Projects

You can find my projects on this GitHub profile.

#### GitHub Actions

This is a test GitHub Action to verify the setup.

### Setup

1. Install dependencies with `npm install`
2. Run the test with `npm run test`

### Test

```yml
name: Test

on:
  push:
    branches: [ main ]

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v2
      - name: Install dependencies
        run: npm install
      - name: Run test
        run: npm run test
      - name: Display success message
        run: echo 'Test passed!'

```