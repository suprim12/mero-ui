# mero-ui

> Modern and minimalist React UI library, originating from Suprim's design.

## Install

```bash
npm i mero-ui
```

## Usage

```jsx
import React, { Component } from "react";

import { MyComponent ,SuprimThemeProvider, theme, GlobalStyles } from "mero-ui";

class Example extends Component {
  render() {
    return (
    <SuprimThemeProvider theme={theme.dark}>
      <GlobalStyles/>
      <MyComponent />;
    </SuprimThemeProvider>
  }
}
```

## License

[MIT](https://github.com/suprim12/suprim-react-ui-public/blob/master/LICENSE)
