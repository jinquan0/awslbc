Multi-Ingress could share One AWS Application LoadBalancer which in a Group

## 进入demo0,demo1,demo2 Pod pv
## 修改html文件
sudo mount -t efs -o tls,accesspoint=fsap-****** fs-06f309*****3ee3a:/ demo0-efsmnt/
sudo mount -t efs -o tls,accesspoint=fsap-****** fs-06f309*****3ee3a:/ demo1-efsmnt/
sudo mount -t efs -o tls,accesspoint=fsap-****** fs-06f309*****3ee3a:/ demo2-efsmnt/
