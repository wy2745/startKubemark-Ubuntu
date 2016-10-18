# startKubemark-Ubuntu
ubuntu script for starting up kubemark

##preparation
  1. Kubernetes binary put in the server folder in your kubernetes root,that is KUBE_ROOT/server, binary can be downloaded in https://storage.googleapis.com/kubernetes-release/release/${release}/kubernetes.tar.gz 
  
  2. A machine to be kubemark master

  3. A kubernetes cluster
  
##step 1
  fill in the ##{}## part of the script, and put it in KUBE_ROOT/test/kubemark to cover the startkubemark.sh
  
##step 2
  run the script
  
##step 3
  cd KUBE_ROOT/test/kubemark/resources, run the command "${kubectl} --kubeconfig=kubeconfig.loc get nodes" to communicate with kubemark master and make sure it start.

