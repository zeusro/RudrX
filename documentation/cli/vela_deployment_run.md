## vela deployment:run

Run deployment workloads

### Synopsis

Run deployment workloads

```
vela deployment:run <appname> [args]
```

### Examples

```
vela deployment:run frontend
```

### Options

```
  -a, --app string     create or add into an existing application group
  -h, --help           help for deployment:run
      --image string   
      --name string    
      --port int        (default 8080)
  -s, --staging        only save changes locally without real update application
```

### Options inherited from parent commands

```
  -e, --env string   specify env name for application
```

### SEE ALSO

* [vela](vela.md)	 - ✈️  A Micro App Platform for Kubernetes.

###### Auto generated by spf13/cobra on 17-Aug-2020
