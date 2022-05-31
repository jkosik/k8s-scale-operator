## k8s-crd
Sample CRD for Kubernetes

Run `crd.yaml` to create CRD.  
Run `demobundle.yaml` to create instance of a Custom Resource.  
  
Next step is to build controller to run logic and reconciliation for Custom Resources.

### More info
An operator is a set of custom resources and a set of controllers. A controller watches for changes to specific resources in the Kubernetes API and reacts by creating, updating, or deleting resources.  
A controller is a reconciliation loop that reads the desired state of a resource from the Kubernetes API and takes action to bring the cluster's actual state closer to the desired state.