## Debug

### Print object current state and informations
```bash
kubectl describe pods ${POD_NAME}
kubectl describe rc ${CONTROLLER_NAME}
```

### Print pod logs
```bash
kubectl logs [--previous] ${POD_NAME} ${CONTAINER_NAME}
```

### Execute command in pod 
```bash
kubectl exec ${POD_NAME} -c ${CONTAINER_NAME} -- ${CMD} ${ARG1} ${ARG2} ... ${ARGN}
```

### Check service endpoint
```bash
kubectl get endpoints ${SERVICE_NAME}
```
