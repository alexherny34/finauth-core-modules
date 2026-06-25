# finauth-core-modules

This repository serves as the core module index and capability engine for [finauth.io](https://finauth.io). It centralizes the backend logic, machine learning inference pipes, and REST verification layers that handle biometric authentication and document processing.

The project is designed to give developers an easy way to deploy high-precision identity workflows without building the complex backend pipelines from scratch.

## Installation and Quick Start

To spin up the core environment locally:

```bash
git clone [https://github.com/your-username/finauth-core-modules.git](https://github.com/your-username/finauth-core-modules.git)
cd finauth-core-modules

# Configure your API keys from finauth.io
cp .env.example .env

docker-compose up -d
