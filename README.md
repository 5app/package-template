# JS Template

This is a template for starting new JS projects at 5app.

## Getting started

Run `npm init` to configure package.json


### For private projects

1. Add to [./package.json](./package.json]) `private: true`.
   This will ensure your project is not accidentally published to *npm*.
2. [Optionally] Remove `.npmrc` file.
   This is used to track dependencies but for published packages this is superfluous
