To display details about the Pod deployed in your cluster, first obtain the unique Pod name with the following command:
```
$ kubectl -n flux get pods
```

Then, copy the unique Pod name to your clipboard and input:
```
$ kubectl -n flux describe pod [your flux pod name here]
```

Example command with sample Pod name:
```
kubectl -n flux describe pod flux-c97899756-wsfhb
```
