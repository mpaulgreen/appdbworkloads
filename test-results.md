// oc get nodes && echo && echo && oc get pods -o wide --watch


// vaniall OCP 
Test1
// when the node that is having mongodb operator pod goes down
mongodb operator pod is reassigned to a new node when a node goes down.


// ops manager has 3 stateful sets
ops-manager-db - 3 pods
ops-manager - 3 pods
ops-manaher-backup-daemon - 1 pod

Test2
// ops-manager-0, ops-manager-backup-daemon-0, ops-manager-db-0 pods was brought down by node failure
ops-manager is still available
the pods are stuck in terminating state. Never saw it recovering


