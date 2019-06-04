# gitbook-plugin-gtalk

![](https://img.shields.io/npm/dt/gitbook-plugin-gtalk.svg)

GitBook Plugin. A modern comment component based on GitHub Issue and Preact.

## Usage

Add it to your `book.json`:

```json
{
  "plugins": ["gtalk"],
  "pluginsConfig": {
    "gtalk": {
      "clientID": "xxx",
      "clientSecret": "xxx",
      "repo": "xxx",
      "owner": "xxx",
      "admin": ["xxx"]
    }
  }
}
```
