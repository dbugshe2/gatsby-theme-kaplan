# A quirky Gatsby Personal Website theme, based on [Wired Elements](https://wiredjs.com/)

_a Work in progress_

(/npm/:interval/:scope?/:gatsby-theme-kaplan)

# Table of Contents

- [Requirments](#requirements)
- [Quick Start](#quick-start)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Requirements

_...Coming Soon_

## Quick Start

```shell
mkdir my-site
cd my-site
yarn init
# install gatsby-theme-kaplan and it's dependencies
yarn add gatsby react react-dom gatsby-theme-kaplan
```

Then add the theme to your `gatsby-config.js`. We'll use the long form
here for education purposes.

```javascript
module.exports = {
  plugins: [
    {
      resolve: "gatsby-theme-kaplan",
      options: {}
    }
  ]
};
```

That's it, you can now run your gatsby site using

```shell
yarn gatsby develop
```

Note that this site doesn't _do_ anything, so you're see a missing
resources error. Create a simple page in `src/pages/index.js` to see a
page on the root url.

```jsx
import React from "react";

export default () => <div>My Site!</div>;
```

## Usage

_...Coming Soon_

## Contributing

_...Coming Soon_

## Doing more with themes

You can use this as a place to start when developing themes. I
generally suggest using [yarn
workspaces](https://yarnpkg.com/lang/en/docs/workspaces/) like the
[gatsby-theme-examples repo
does](https://github.com/ChristopherBiscardi/gatsby-theme-examples),
but using `yarn link` or `npm link` is a viable alternative if you're
not familiar with workspaces.

## License

MIT License

Copyright (c) 2020 Maroof Shittu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
