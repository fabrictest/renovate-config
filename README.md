```sh
cat >renovate.json <<EOF
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>fabrictest/renovate-config"
  ],
  "forkProcessing": "enabled"
}
EOF
git add renovate.json
git commit -m 'chore: automate dependency updates'
git push
```
