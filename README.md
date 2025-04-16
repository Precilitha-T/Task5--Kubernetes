# Task5--Kubernetes
Kubernetes-Cluster-with-Minikube
Install Minikube on an Amazon EC2 instance using the none driver and deploying a simple NGINX app exposed via a NodePort.

Prerequisites
1. Amazon Linux EC2 instance (t2.medium or higher recommended)
2. Docker installed and running
3. Sudo/root access
kubectl and Minikube binaries
4. Installation and setup steps
Install kubectl
Install Minikube and dependencies
5. Start Minikube with none drive
Create deployment.yaml and service.yaml
6. Apply the configurations kubectl apply -f deployment.yaml kubectl apply -f service.yaml
7. Deploy Kubectl kubectl get deploy
8. Check pod and service status kubectl get pods kubectl get svc nginx-service
Add Security Groups Ensure the following inbound rules in your EC2 security group: Port 22 (SSH) Port 80 (HTTP) Port 32065 (NodePort) Optional: Port Range 30000–32767 (for future NodePort services)
9. Access from browser/ ngnix-server
10. Cleanup minikube delete

# Screenshots

![Screenshot (240)](https://github.com/user-attachments/assets/df019337-ff42-42df-8951-abcf8c361260)

![Screenshot (242)](https://github.com/user-attachments/assets/d556889b-c148-49de-ac68-2ca736dc6d1b)

![Screenshot (243)](https://github.com/user-attachments/assets/c1bed9fe-d776-458c-b066-130c10c132f9)

![Screenshot (244)](https://github.com/user-attachments/assets/c9536968-f07f-43d1-a019-9ecc2d1bf1d2)

![Screenshot (245)](https://github.com/user-attachments/assets/ddb860cb-c782-4f62-81db-0bd7f0640782)

![Screenshot (246)](https://github.com/user-attachments/assets/4dd2ff38-ca6e-47d8-97a8-4bda91d63d0a)

![Screenshot (247)](https://github.com/user-attachments/assets/f78b0b37-be23-4027-bb64-0830d7811cef)

![Screenshot (248)](https://github.com/user-attachments/assets/ad83c912-56e3-48d4-8057-7bd28cdf6800)






