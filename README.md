# CLOGZ - A Nicer Console Log

Do you find it difficult tracing all your Console.Logs on the browser's Console?

Clogs highlights your console.log, so it's easier to find.

![Logo](https://user-images.githubusercontent.com/103944777/179792503-5e9ba123-1166-412c-9ddc-d92d294f9b69.png)

## Installation

Currently this module is only availbale for React JS

Install with npm

```bash
  cd my-project
  npm install clogz

```

## Usage/Examples

```javascript
import clogz from "clogz/index.js";

clogz("your text here");
```

You can also use `clogs()` with variables like this:

```javascript
import clogz from "clogz/index.js";
const myText = "This is console log with logz";

clogz(myText);
```

## Roadmap

Upcoming features:

- Customize colours
- Unique colours for every clogz() call

## Support

For support, please comment on the Github repo.
