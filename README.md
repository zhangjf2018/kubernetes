# kubernetes 部署记录

ETCD状态查看
etcdctl --endpoints=https://192.168.44.142:2379 --ca-file=/etc/kubernetes/ca/ca.pem   --cert-file=/etc/kubernetes/ca/etcd/etcd.pem   --key-file=/etc/kubernetes/ca/etcd/etcd-key.pem cluster-health health

K8S组件状态
kubectl get componentstatus 或 kubectl get 
