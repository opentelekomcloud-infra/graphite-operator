# graphite-operator
K8 operator for Graphiteapp

# Ensuring service user can created privileged pods:

oc create clusterrolebinding deployer-privileged --clusterrole system:openshift:scc:privileged --serviceaccount MY_NAMESPACE:deployer
