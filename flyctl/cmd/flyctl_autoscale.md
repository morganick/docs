# _flyctl autoscale_

Autoscaling App resources

### About

Autoscaling amount of application instances.

### Usage
```
flyctl autoscale [command] [flags]
```

### Available Commands
* [balanced](/docs/flyctl/autoscale-balanced/)	 - Configure a traffic balanced App with params (min=int max=int)
* [disable](/docs/flyctl/autoscale-disable/)	 - Disable autoscaling
* [set](/docs/flyctl/autoscale-set/)	 - Set current models autoscaling parameters
* [show](/docs/flyctl/autoscale-show/)	 - Show current autoscaling configuration
* [standard](/docs/flyctl/autoscale-standard/)	 - Configure a standard balanced App with params (min=int max=int)

### Options

```
  -a, --app string      App name to operate on
  -c, --config string   Path to an app config file or directory containing one (default "./fly.toml")
  -h, --help            help for autoscale
```

### Global Options

```
  -t, --access-token string   Fly API Access Token
  -j, --json                  json output
  -v, --verbose               verbose output
```

### See Also

* [flyctl](/docs/flyctl/help/)	 - The Fly CLI
* [flyctl scale](/docs/flyctl/scale/)	 - Scale resources (memory/cpu)
* [Scaling and Autoscaling](/docs/reference/scaling/)	 - Guide to Scaling and Autoscaling

