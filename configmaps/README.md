########
Create configmap with settings
echo hello world >> index.html

k create cm webindex --from-file=index.html

--Edit yml

--Deploy nginx app with configmap volumes

k apply -f webserver.yml

--Test on pod file from yml

k exec -it webserver-76d44586d-7z7cw -- /bin/bash










#######
--basura--

echo hello world >> index.html

  475  k create cm weindex --from-file=index.html

  476  k get cm

  477  k delete cm weindex --from-file=index.html

  478  k delete cm weindex

  479  k delete cm webindex --from-file=index.html

  480  k create cm webindex --from-file=index.html



       k get deployment.apps webserver -o yaml >> ./webserver.yml

  504  vim webserver.yml

  505  k apply -f webserver.yml

  506  k get pods

  507  k get deployment

  508  k apply -f webserver.yml

  509  vim webserver.yml


  536  k exec -it webserver-76d44586d-7z7cw -- /bin/bash

  537  ll

  538  k get configmap

  539  k describe configmap


