# Emotion Snippets for React apps by iJS

Thanks for giving this a go. Hope this helps and makes your coding more efficient and fun.

## Hello.

Animations coming soon.

> Pull requests are most welcome!

## Installation

- Launch the Command Pallete (Ctrl + Shift + P or ⌘Cmd + Shift + P) and type "Install Extensions" (or navigate from the sidebar to Extensions tab).
- In search box type in "iJS" and choose the Emotion Snippets
- Install the extension (you may need to relaunch VS Code)
- Get a coffee, a cookie and celebrate by expanding some emotion.js snippets!

## Supported languages (file extensions)

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

## Emotion.js Snippet Contents

|           Trigger | Content                                                   |
| ----------------: | --------------------------------------------------------- |
|       `emimpcss→` | Import css from @emotion/core                             |
|    `emimpstyled→` | Import styled from emotion                                |
|     `styledcomp→` | Declare styled component                                  |
| `styledwrapcomp→` | Declare custom component wrapped in a styled component    |
|         `stprop→` | Universal destructuring of a prop template literal        |
|     `emimptheme→` | Import useTheme from emotion                              |
|     `emusetheme→` | Declare them with useTheme() from emotion                 |
|          `emcss→` | Declared an emotion css style variable                    |
|       `emobjcss→` | Declared an emotion css style variable with object styles |
|       `emimpjsx→` | Imports emotion jsx prop                                  |
|    `emimpjsxcss→` | Imports emotion jsx and css props                         |

- More snippets to come, stay tuned!

## Expanded Snippets

### emimpcss - Import css from @emotion/core

```javascript
import { css } from "@emotion/core";
```

### emimpstyled - Import styled from emotion

```javascript
import styled from "@emotion/styled";
```

### styledcomp - Declare styled component

```javascript
const StyledComp| = styled.div`
  |
`;
```

### styledwrapcomp - Wrap custom component with emotion styled component

```javascript
const StyledComp| = styled(CustomComp|)`
  |
`;
```

### stprop - Import css from @emotion/core

```javascript
  ${({ | }) => | }
```

### emimptheme - Import emotion's useTheme

```javascript
import { useTheme } from "emotion-theming";
```

### emusetheme - Declare them with useTheme() from emotion

```javascript
const theme = useTheme();
```

### emcss - Declared an emotion css style variable

```javascript
const style| = css`
  |;
`;
```

### emobjcss - Declared an emotion css style variable with object styles

```javascript
const objectStyles| = css({
    |,
})
```

### emimpjsx - Imports emotion jsx prop

```javascript
// below comment line is required
// it tells babel how to convert properly
/** @jsx jsx */
import { jsx } from "@emotion/core";
```

### emimpjsxcss - Imports emotion jsx and css props

```javascript
// below comment line is required
// it tells babel how to convert properly
/** @jsx jsx */
import { jsx, css } from "@emotion/core";
```

## Release Notes

## [1.0.0] - 2020 March 3rd

### Added

#### Snippets:

- `gip→` | getInitialProps() outside component
- `ccgip→` | static getInitialProps() inside class component
- `gipaq→` | NextJS getInitialProps() withApollo() expose query

-       `emimpcss→` | Import css from @emotion/core
- `emimpstyled→` | Import styled from emotion
-     `styledcomp→` | Declare styled component
- `styledwrapcomp→` | Declare custom component wrapped in a styled component
-         `stprop→` | Universal destructuring of a prop template literal
-     `emimptheme→` | Import useTheme from emotion
-     `emusetheme→` | Declare them with useTheme() from emotion
-          `emcss→` | Declared an emotion css style variable
-       `emobjcss→` | Declared an emotion css style variable with object styles
-       `emimpjsx→` | Imports emotion jsx prop
- `emimpjsxcss→` | Imports emotion jsx and css props

- Initial Emotion Snippets Release

**Enjoy!**
/ Scott Agirs
