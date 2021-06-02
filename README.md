## Status of this project: Brand new, very brittle, constantly changing

# nginx-webserver-k8s-deployment

Requires a load balancer like MetalLB

Exec into the sidecar to scp content into /mnt (which is .../html for nginx): `kubectl exec -it  nginx-deployment-648d84889b-q8gc5  -c sidecar-container -- /bin/sh`
