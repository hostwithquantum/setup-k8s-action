# setup-k8s-action

A composite action to setup k8s tools, config and populate the `KUBECONFIG` env variable.

Options:

- environment
- config-staging
- config-production
- location (of the Kubernetes config)

Uses:

- [`yokawasa/action-setup-kube-tools`](https://github.com/yokawasa/action-setup-kube-tools)
