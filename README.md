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

For more details on this usage, refer to the official Argo CD documentation.

## Contributing

Contributions to this repository are welcome! If you have any improvements, additional examples, or fixes, feel free to open a pull request.

## License

This repository is licensed under the MIT License.
