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

