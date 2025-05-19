kubectl apply -f all-in-one.yml
kubectl apply -f ingress.yml
kubectl port-forward -n ingress-nginx svc/ingress-nginx-controller 80:80 --address=0.0.0.0
browse it.........
http://3.88.56.195.nip.io/shop

http://3.88.56.195.nip.io/nginx

http://3.88.56.195.nip.io/apache
