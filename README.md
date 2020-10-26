# loki-stack
This is a version of the loki stack helm chart that allows you to run loki in microservices or horizontally scalable mode. 
To choose a mode, specify one of loki.standaloneMode or loki.modularMode as 'true' (and the other as 'false') in values.yaml:
```
# This will enable microservices mode
loki:
  modularMode: true
  standaloneMode: false
```
