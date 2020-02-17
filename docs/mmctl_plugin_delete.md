## mmctl plugin delete

Delete plugins

### Synopsis

Delete previously uploaded plugins from your Mattermost server.

```
mmctl plugin delete [plugins] [flags]
```

### Examples

```
  plugin delete hovercardexample pluginexample
```

### Options

```
  -h, --help   help for delete
```

### Options inherited from parent commands

```
      --format string                the format of the command output [plain, json] (default "plain")
      --insecure-sha1-intermediate   allows to use insecure TLS protocols, such as SHA-1
      --strict                       will only run commands if the mmctl version matches the server one
```

### SEE ALSO

* [mmctl plugin](mmctl_plugin.md)	 - Management of plugins
