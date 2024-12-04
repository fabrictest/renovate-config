# renovate-config

> [Renovate][] settings
> shared across [Fabric Test][] projects

## Usage

Paste the following content
in a `renovate.json` file in the repository root:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>fabrictest/renovate-config"
  ]
}
```

[fabric test]: https://fabricte.st/
[renovate]: https://www.mend.io/renovate/
