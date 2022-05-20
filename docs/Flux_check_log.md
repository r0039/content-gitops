To display the log produced by the fluxd daemon running as a Deployment in your cluster, enter the command:
```
$ kubectl -n flux logs deployment/flux
```

This assumes you have deployed flux to the flux namespace.
