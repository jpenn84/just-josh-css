# Just Josh CSS

A little CSS library for my projects. Feel free to use it and build upon it! 

I believe the true way to pull your boots up by the boot strap is to make your own artisinal bootstraps and not use THE Bootstrap.

Jokes aside, this is just supposed to be a CSS library to use across my  personal sites in order to maintain consistent and continuous personal branding. of course, if a lot of sites start using this, 

## Testing

To test styles, each style file should be paired with an html page where only that project style is tested.

A separate `test/teststyles.scss` file should hold the styles used to support testing of the styles being tested.

This is a place where you DO repeat yourself. Even if the test support styles match a project style exactly, you should copy these values instead of using product styles. This ensures product updates do not interfere with the tests.

## Run Locally

Clone the project

```bash
  git clone https://github.com/jpenn84/just-josh-css.git
```

Go to the project directory

```bash
  cd just-josh-css
```

Install dependencies

```bash
  npm install
```

Run sass

```bash
  npm run build
```

Open the html test file

## Authors

- [@jpenn84](https://www.github.com/jpenn84)

## Feedback

Do you have any opinion-based feedback that you want to give to me? DON'T! Fork it and change it yourself. It is highly encouraged, and it makes me happy inside that the nummer increments by 1.

Do you see a bug or have an optimization? Please open an issue. Feel free to fork the project and open a branch and a PR against main. Or just put the code in your issue and I'll play around with it for a bit myself.