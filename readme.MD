	
#helm installation
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-4

chmod 700 get_helm.sh

 ./get_helm.sh
 helm version
 ================================
 helm commands
 ----------------------------------
 helm install <chart-name> .
helm list -> listing all the charts
helm upgrade nginx .
helm history nginx
helm rollback <name> <revision-number>
 ====================================