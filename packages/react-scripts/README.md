# @deondigital/react-scripts

This package is a Deon Digital specific fork of
[react-scripts](https://www.npmjs.com/package/react-scripts). The code is found
at [https://github.com/deondigital/create-react-app-with-files].

Use it by running
`npx create-react-app my-app-name --template typescript --scripts-version @deondigital/react-scripts`
when creating your app, or just update the `react-scripts` dependency in you
`package.json` to `@deondigital/react-scripts`.

The only current difference from stock
[react-scripts](https://www.npmjs.com/package/react-scripts) is that it outputs
the files from the development server instead of serving them from memory. You
can configure where it outputs it by setting the `BUILD_PATH` environment
variable, and stop the browser from starting with the in-memory files by setting
`BROWSER=none`.

To update the package, clone the repo and make your changes inside
`packages/react-scripts` or merge a new version from
[https://github.com/facebook/create-react-app]. Push your changes, remember to
update the `README.md` and the version in `package.json` if applicable, `cd` to
`packages/react-scripts` and run `npm publish`.
