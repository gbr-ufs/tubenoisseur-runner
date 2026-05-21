# `CONTRIBUTING.md`

1. Add your channel to the channel matrix under [.github/workflows/tubenoisseur.yaml](.github/workflows/tubenoisseur.yaml)
2. If necessary, already add any domain exclusions to the channel's state:


`tubenoisseur/foo/foo.json`

```json
{

  "channelHandle": "foo",
  "excludedDomains": [
    "foo.com",
    "bar.com"
  ]
}
```
