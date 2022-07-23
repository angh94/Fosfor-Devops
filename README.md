1. Create a DeaemonSet yml
2. Run DeaemonSet yml
3. Check the rollout history
4. Confirm if DaemonSet is running by running the command - kubectl get ds
5. You can roll back to any version by running the command
	- kubectl rollout undo daemonset <daemonset-name> --to-revision=<revision>
6. Screenshots are upload to github
