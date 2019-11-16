#how to create azure storage on openshift 
oc create -f  azure-file-sc.yaml
oc create -f azure-pvc-roles.yaml
oc create -f azure-file-pvc.yaml
