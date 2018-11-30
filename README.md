# renovate-config

Renovate bot [preset settings][presets] that can be extended or used directly in your projects.
Config can still be overriden in each individual project, for flexibility.

## How to use
In `package.json` of a project, add the following section:
```
  "renovate":{
    "extends": [
      "github>pagerinc/renovate-config"
    ]
  }
```

[presets]: https://renovatebot.com/docs/config-presets
