# owncloud-kubernetes-rook
Running OwnCloud on Kubernetes using Rook Ceph for storage.

All manifests, besides, e.g., RBAC objects, are namespace-less.
The RBAC objects are using the Namespace `owncloud`, so be sure to search and replace for `namespace: owncloud`.
