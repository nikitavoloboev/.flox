# Personal [Flox](https://flox.dev/) global env

Using it to run `daemons` in background and setup global `$PATH` env with executables to run.

See [env/manifest.toml](env/manifest.toml) for the config.

## Use

Clone `.flox` repo into `~/.flox`, then run:

```
flox activate -s
```

And I often run:

```
flox services logs --follow
```

To see the logs. I currently do it in separate [Ghostty](https://mitchellh.com/ghostty) instance.
