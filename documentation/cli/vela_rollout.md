## vela rollout

Attach rollout trait to an app

### Synopsis

Attach rollout trait to an app

```
vela rollout <appname> [args]
```

### Examples

```
vela rollout frontend
```

### Options

```
  -a, --app string           create or add into an existing application group
      --batch int             (default 2)
  -h, --help                 help for rollout
      --maxUnavailable int    (default 1)
      --replica int           (default 3)
  -s, --staging              only save changes locally without real update application
```

### Options inherited from parent commands

```
  -e, --env string   specify env name for application
```

### SEE ALSO

* [vela](vela.md)	 - ✈️  A Micro App Platform for Kubernetes.

###### Auto generated by spf13/cobra on 17-Aug-2020
