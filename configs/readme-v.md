diting Your Config:

In your fork, navigate to configs/noi.mode.json.

Edit this JSON file to include your preferred structure, websites, and folders. The format should look like this:

```
{
  "name": "Custom Mode",
  "version": "1.0.0",
  "modes": [
    {
      "id": "my@tools",
      "parent": 0,
      "dir": true,
      "text": "My Tools"
    },
    {
      "id": "my:github",
      "parent": "my@tools",
      "text": "GitHub",
      "url": "https://github.com"
    }
  ]
}
```

