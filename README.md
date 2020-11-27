# CI/CD example jenkins/k8s

#important to jenkins to connect ssh on remote:
1. On remote: ssh-keygen -t rsa
2. cp ~/.ssh/id_rsa.pub > ~/.ssh/authorized_keys
3. add the provate key id_rsa "content" to jenkins credentials
