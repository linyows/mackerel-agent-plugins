mackerel-plugin-memcached
=========================

Memcached custom metrics plugin for mackerel.io agent.

## Synopsis

```shell
mackerel-plugin-memcached [-host=<host>] [-port=<port>] [-tempfile=<tempfile>]
```

## Example of mackerel-agent.conf

```
[plugin.metrics.memcached]
command = "/path/to/mackerel-plugin-memcached"
```

