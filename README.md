# helm-airflow
This repository hosts Helm charts for deploying Apache Airflow on Kubernetes clusters. The Helm charts provided here offer a convenient way to deploy, manage, and scale Airflow instances on Kubernetes.

## Table of Contents
- [Introduction](#introduction)
- [Usage](#usage)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Apache Airflow is an open-source platform to programmatically author, schedule, and monitor workflows. By using Helm charts, you can easily deploy Airflow on Kubernetes clusters with customizable configurations for various environments.

## Usage
To deploy Apache Airflow on Kubernetes using Helm, follow these steps:

1. **Prerequisites**: Ensure that you have access to a Kubernetes cluster where you want to deploy Airflow. You should also have Helm installed on your local machine.

2. **Clone the Repository**: Clone this repository to your local machine:

```
git clone https://github.com/lukedappleton/helm-airflow.git
```

3. **Customize Configuration**: Navigate to the `helm-airflow` directory and customize the Helm chart values according to your requirements. You can modify parameters such as the Airflow version, database settings, and resource allocations.

4. **Deploy Airflow**: Use Helm to install the Airflow Helm chart:

```
helm install airflow ./helm-airflow
```

## Prerequisites
Before deploying Apache Airflow using Helm, make sure you have the following prerequisites:
- Access to a Kubernetes cluster (such as GKE) where you want to deploy Airflow.
- Helm installed on your local machine.
- Basic knowledge of Helm and Kubernetes concepts.

## Installation
There is no separate installation process for this repository. Follow the usage instructions mentioned above to deploy Airflow on your Kubernetes cluster using Helm.

## Contributing
Contributions to this repository are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).