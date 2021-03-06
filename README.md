# โ๏ธ Lucky Jumpstart

This is a template project for web applications using [Lucky](https://luckyframework.org).

![Lucky Jumpstart CI](https://github.com/stephendolan/lucky_jumpstart/workflows/Lucky%20Jumpstart%20CI/badge.svg)

### How to use it?

- Click [this link](https://github.com/stephendolan/lucky_jumpstart/generate)
- Run `./script/rename_template_app` to rename the template application
- Run `./script/setup`
- Run `lucky dev`

### Why use a template?

There are quite a few things I find myself adding to every Lucky application out of the box, and this serves as a bit of a better starting point than the default generated application.

### What's in the box?

#### Development

- ๐ณ &nbsp; A [DockerCompose](https://docs.docker.com/compose/) file for running your application database, included in `Procfile.dev`

#### Dependencies

- ๐ &nbsp; Up-to-date Crystal dependencies
- ๐งถ &nbsp; Up-to-date Yarn dependencies

#### Tooling

- ๐จ &nbsp; [TailwindCSS 2.0](https://tailwindcss.com) for better styling
- ๐ &nbsp; [Tailwind Typography](https://tailwindcss.com/docs/typography-plugin) for prose
- ๐ &nbsp; [Tailwind Forms](https://github.com/tailwindlabs/tailwindcss-forms) to make styling forms easier
- ๐ฅ &nbsp; [Tailwind Aspect Ratio](https://github.com/tailwindlabs/tailwindcss-aspect-ratio) for setting fixed aspect ratios
- ๐ &nbsp; [StimulusJS](https://stimulusjs.org) for JavaScript sprinkles
- ๐ &nbsp; [TypeScript](https://typescript.org) for keeping JavaScript cleaner

#### Functionality

- ๐ง &nbsp; Email confirmation of users

#### CI/CD

- ๐ค &nbsp; A handy dandy [Dependabot](https://dependabot.com/) configuration file

- A working GitHub Actions workflow with:

  - ๐ &nbsp; [Prettier](https://prettier.io/)
  - ๐ &nbsp; [Crystal Format](https://crystal-lang.org/reference/using_the_compiler/#crystal-tool-format)
  - ๐ฆ  &nbsp; [Ameba](https://github.com/crystal-ameba/ameba)
  - ๐ &nbsp; [Crystal Spec](https://crystal-lang.org/api/latest/Spec.html)

#### Deployment

- ๐ &nbsp; [Digital Ocean App Platform](https://www.digitalocean.com/docs/app-platform)
- ๐พ &nbsp; [Heroku](https://luckyframework.org/guides/deploying/heroku)
