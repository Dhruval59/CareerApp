# CareerApp
Build your career
- Dockerize the application and pushed the image to dockerhub
- Created EKS cluster
- Deployed the application using deployment.yaml (Creating deployment with 2 replicasets and LoadBalancer service) through github actions

```
[ec2-user@ip-172-31-18-75 ~]$ kubectl get deployments
NAME         READY   UP-TO-DATE   AVAILABLE   AGE
career-app   2/2     2            2           15m
[ec2-user@ip-172-31-18-75 ~]$ kubectl get svc
NAME                 TYPE           CLUSTER-IP       EXTERNAL-IP                                                               PORT(S)        AGE
career-app-service   LoadBalancer   10.100.210.222   a49926dd2206c469480051cb605bb69a-1778260546.us-west-2.elb.amazonaws.com   80:30672/TCP   16m
kubernetes           ClusterIP      10.100.0.1       <none>                                                                    443/TCP        25m
```
<img width="1440" alt="image" src="https://github.com/user-attachments/assets/fc8b88ea-8302-4f6f-9a6b-8c29c46fb0f3">
