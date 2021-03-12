QUickstart:
1. Create flux secret namespace: kubectl create ns flux-system
2. Create secret 
 kubectl create secret -n flux-system  generic my-super-secret-data --from-literal=username=USERNAME --from-literal=password=PASSWORD
3. Bootstrap flux (according to the doc)
