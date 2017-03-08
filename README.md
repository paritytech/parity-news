# parity-news

Published under `paritynews` on Registry for network-specific updates.

## format

```
{
  "1": {
    "items": [
      {
        "title": "<title>",
        "background": "<http://image url>",
        "markdown": "<content>"
      },
      {
        ...
      },
      {
        ...
      }
    ]
  }
}
```

- `"1"` refers to the current content-type version, only `"1"` currently available
- `"items"` is an array of items, left-top right, 3 per row
- `"background"` should refer to hash-links or other permanent resources
- Optionally [styles](https://github.com/jacogr/parity-news/blob/6831146129550edba5e432d31518f7e0be1d7253/news.json#L18) can be defined

## deploy

- Register content with GithubHint (ensure hash-links are used)
- Update `paritynews` on registry (meta `CONTENT`)
