# To add load on the php-apache application
1. Create a sample pod using ubuntu base image and exec into the pod

## Reference : https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale-walkthrough/
2. Run the below command inside the pod  
``` while true; do wget -q -O- http://php-apache; done ```
