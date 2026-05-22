# Deployment

kubectl apply -f kubernetes/

Verify:

kubectl get pods -n nexoryx-gpu
kubectl get svc -n nexoryx-gpu
kubectl get ingress -n nexoryx-gpu
