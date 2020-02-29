# opmanager
ManageEngine Opmanager on docker

To quickly get started running use the following command:
```bash
docker run --detach --publish 8060:8060 babim/opmanager:latest
```
```
volume:
/opt/ManageEngine/OpManager
```

run manual with CMD /usr/sbin/init and download, install apps
change to CMD default after install apps