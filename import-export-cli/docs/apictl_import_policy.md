## apictl import policy

Import a Policy

### Synopsis

Import a Policy in an environment or Import a Policy to an environment

```
apictl import policy [flags]
```

### Examples

```
apictl import policy rate-limiting -f ~/CustomPolicy -e production --u
```

### Options

```
  -h, --help   help for policy
```

### Options inherited from parent commands

```
  -k, --insecure   Allow connections to SSL endpoints without certs
      --verbose    Enable verbose mode
```

### SEE ALSO

* [apictl import](apictl_import.md)	 - Import an API/API Product/Application to an environment
* [apictl import policy rate-limiting](apictl_import_policy_rate-limiting.md)	 - Import Throttling Policy

