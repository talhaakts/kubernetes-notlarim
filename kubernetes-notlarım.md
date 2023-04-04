# kubectl-command-notes

podları listeler
#kubectl get pods 

nodeları listeler
#kubectl get node

kümelerdeki nesnelerin ayrıntılı bilgilerini görüntüler
#kubectl describe

oluşturulan konfigürasyon dosyasına göre nesneleri oluşturur veya günceller
#kubectl create -f  x.yaml  && kubectl apply -f x.yaml

nesne oluşturmaya ve image belirlemizi sağlar
#kubectl run x --image=ximage

liste görünümünde nesneler hakkında daha fazla bilgi almamızı sağlar
#kubectl get pods -o wide

varolan pod'u silmemizi sağlar
#kubectl delete pod podname

varolan node'u silmemizi sağlar
#kubectl delete node nodename

replica set oluşturmamızı sağlar
#kubectl create -f xxx.yaml

varolan replicasetlerimizi listeler
#kubectl get replicaset

replica setleri silmemizi sağlar | replica set altında çalışan tüm podlar silinir
#kubectl delete replicaset myapp-xxx 

replica set değişikliklerini güncellememizi sağlar
#kubectl replace -f xxx.yam

terminal üzerinden yaml dosyamızı modify etmemizi sağlar
#kubectl scale --replicas=6 -f xxx.yaml


