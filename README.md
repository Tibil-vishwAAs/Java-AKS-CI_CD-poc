# Java-AKS-CI_CD-poc

## This is example Java spring boot code, consists  one api ```/employees```. Which provides the list of available employees

## Build
``` mvn clean install```
# Test
``` curl --location 'http://localhost:8080/employees' ```

# Iterative call
```counter=1; while true; do echo "Execution $counter:"; curl --location 'http://192.168.49.2:32363/employees'; echo; ((counter++)); sleep 5; done```

