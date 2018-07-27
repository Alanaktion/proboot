# Proboot

*An opinionated Bootstrap 4 theme for web apps, based on [tabler](https://github.com/tabler/tabler)*

Out of the box, Bootstrap 4 is a very simplistic, unopinionated framework. For most cases, particularly when an existing UI style needs to be kept, this is excellent. Sometimes though, it's easier to start from a slightly prettier base. Proboot is designed to be a drop-in replacement for Bootstrap 4, intended to be implemented early-on in projects, and primarily aimed at complex UIs rather than clean landing pages.

## Usage

Install with npm:

```bash
npm install proboot
```

Then just include Proboot in your SCSS file:

```scss
@import 'node_modules/proboot/scss/proboot';
```

You can override any of the standard Bootstrap variables, and the Proboot ones, by defining them before importing proboot. If you only need certain components, they can be imported individually instead of including the main proboot file.
