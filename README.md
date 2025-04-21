# LSC-kubernetes
# Commends:
<ul>
    <li>helm repo add nfs-ganesha-server-and-external-provisioner https://kubernetes-sigs.github.io/nfs-ganesha-server-and-external-provisioner/</li>
    <li>helm install nfs-server-provisioner nfs-ganesha-server-and-external-provisioner/nfs-server-provisioner   --set storageClass.name=nfs-storage   --set storageClass.defaultClass=true</li>
    <li>kubectl create namespace lsc</li>
    <li>kubectl apply -f pvc.yaml -n lsc</li>
    <li>kubectl apply -f nginx-deployment.yaml -n lsc</li>
    <li>kubectl apply -f nginx-service.yaml -n lsc</li>
    <li>kubectl apply -f nginx-service.yaml -n lsc</li>
    <li>kubectl get svc -n lsc</li>
</ul>