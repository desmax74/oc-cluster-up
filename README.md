# oc-cluster-up
OKD 4.0.0 form master with the admin console and operatore-lifecycle-manager

```
docker run -it -p 9000:9000 --privileged -v /tmp/:/tmp/ -v /var/run/docker.sock:/var/run/docker.sock gustavonalle/oc-cluster-up
```