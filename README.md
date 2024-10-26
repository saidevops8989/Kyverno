# Kyverno
Kyverno is a policy engine designed for Kubernetes and 
Kyverno policies can validate, mutate, generate, and cleanup Kubernetes resources, and verify image signatures and artifacts to help secure the software supply chain


K8s cluster with out Kyverno 
will look like this it mean doesnot have any restrictions

<img width="635" alt="Screenshot 2024-10-25 at 8 53 57 PM" src="https://github.com/user-attachments/assets/73394e62-69c0-4d3c-b624-34fb224013ca">

it doesn't have restrictions 
POD running as root user
POD doesn't have any limits 
POD has not labels
Everyone can change configmaps

By enforcing Kyverno polciy we can restrict them


