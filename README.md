# Argocd Examples

This repository contains examples showcasing the usage of Argo CD for managing Kubernetes applications. It demonstrates how to leverage Argo CD's features and best practices for application deployment and management.

## Usage

To use these examples, follow the steps below:

1. Clone this repository to your local machine.

2. Install Argo CD in your Kubernetes cluster. Refer to the official Argo CD documentation for installation instructions.

3. Apply the example manifests using Argo CD.

4. Monitor the status of the Argo CD application.

5. Explore other examples in this repository and apply them accordingly.

## File Details

### app-of-apps-helm.yaml

This file `app-of-apps-helm.yaml` demonstrates the creation of an Application of Applications using a Helm chart. It showcases how to use the `ARGOCD_APP_SOURCE_REPO_URL` environment variable to reference the Git repository URL, allowing you to utilize Helm values from an external Git repository without hardcoding the URL in the application's YAML file.

### app-umbrella-helm.yaml

This file `app-umbrella-helm.yaml` contains an example of an Umbrella chart. It allows you to use a chart from an Helm repository and customize it with values from the reference Git repository. This enables you to easily deploy and manage complex applications with Helm charts while leveraging the flexibility of external Git repositories for configuration and customization.

For more details on this usage, refer to the official Argo CD documentation.

### gitlab-private-repo-secret.yaml

The gitlab-private-repo-secret.yaml file contains a secret used for authenticating ArgoCD to a private GitLab repository using a token.

## Contributing

Contributions to this repository are welcome! If you have any improvements, additional examples, or fixes, feel free to open a pull request.

## License

This repository is licensed under the MIT License.
