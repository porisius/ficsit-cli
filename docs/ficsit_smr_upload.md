## ficsit smr upload

Upload a new mod version

```
ficsit smr upload [flags] <mod-id> <file> <changelog...>
```

### Options

```
      --chunk-size int     Size of chunks to split uploaded mod in bytes (default 10000000)
  -h, --help               help for upload
      --stability string   Stability of the uploaded mod (alpha, beta, release) (default "release")
```

### Options inherited from parent commands

```
      --api-base string             URL for API (default "https://api.ficsit.app")
      --api-key string              API key to use when sending requests
      --cache-dir string            The cache directory (default "/home/vilsol/.cache/ficsit")
      --dry-run                     Dry-run. Do not save any changes
      --graphql-api string          Path for GraphQL API (default "/v2/query")
      --installations-file string   The installations file (default "installations.json")
      --local-dir string            The local directory (default "/home/vilsol/.local/share/ficsit")
      --log string                  The log level to output (default "info")
      --log-file string             File to output logs to
      --pretty                      Whether to render pretty terminal output (default true)
      --profiles-file string        The profiles file (default "profiles.json")
      --quiet                       Do not log anything to console
```

### SEE ALSO

* [ficsit smr](ficsit_smr.md)	 - Manage mods on SMR

###### Auto generated by spf13/cobra on 14-Oct-2022