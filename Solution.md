Please review- 
changelog for the issues fixed in Kubernetes:

1. Changed Port: The service port was updated to the correct configuration so it works as expected.
2. CrashBackLoop Fixed: Solved an issue where containers were repeatedly restarting due to the CrashLoopBackOff error.
3.Image Issue Fixed: Fixed problems with the container image, such as using the wrong version or a missing image.
4.Taint Removed: Removed unnecessary taints from nodes, making it possible for pods to be scheduled on them.