kubesudo
========

Run kubectl command as a service account.

This is useful for testing rbac roles bound to service accounts.

# Usage

    kubesudo kube-system:default get pod -n kube-system

    No resources found.
    Error from server (Forbidden): pods is forbidden: User "system:serviceaccount:kube-system:default" cannot list pods in the namespace "kube-system"

# License

MIT: https://clkao.mit-license.org/
