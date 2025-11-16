## MVP

https://github.com/mkhomytsya/go-demo-app

kubectl port-forward svc/ambassador -n demo 8088:80

curl -F 'image=@demo.png' localhost:8088

curl -F 'image=@demo.png' localhost:8088/img/