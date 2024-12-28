# jenkins-setup
Jenkins infra helm charts

## License

[Apache 2.0](LICENSE)

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

## Code of Conduct

Please see [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for more details.

## Security

Please see [SECURITY.md](SECURITY.md) for more details.

## Support

Please see [SUPPORT.md](SUPPORT.md) for more details.

## Contributors

Please see [CONTRIBUTORS.md](CONTRIBUTORS.md) for more details.

## Helpful Links

- [Jenkins](https://jenkins.io/)
- [Helm](https://helm.sh/)
- [Kubernetes](https://kubernetes.io/)

## Helm charts

- [jenkins-setup](https://github.com/njampani123/jenkins-setup)

## Helm commands

- `helm install jenkins-setup jenkins-setup/jenkins-setup`
- `helm upgrade jenkins-setup jenkins-setup/jenkins-setup`
- `helm delete jenkins-setup`

## Setting Kubernetes Namespace context

- `kubectl config set-context --current --namespace=jenkins-setup`

## Setting Kubernetes context

- `kubectl config use-context jenkins-setup`
