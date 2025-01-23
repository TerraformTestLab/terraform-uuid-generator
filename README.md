# 🌟 Terraform UUID Generator 🎲

## 📝 Overview

`terraform-uuid-generator` is a lightweight Terraform configuration designed to generate unique identifiers during each execution. This utility is particularly useful for scenarios requiring runtime tracking, debugging, or creating consistently unique markers across `terraform apply` operations.

## 🚀 Features

- **Universally Unique Identifier (UUID) Generation**: Creates a new UUID on every Terraform execution
- **Execution Signature**: Produces a random identifier based on the current runtime
- **Zero Infrastructure Dependency**: No cloud resources or external dependencies required
- **Lightweight and Simple**: Minimal configuration with maximum utility

## 🔧 Prerequisites

- Terraform 1.0+
- HashiCorp Random Provider

## 💻 Usage

### Initialization

```bash
terraform init
```

### Apply Configuration

```bash
terraform apply
```

Each `apply` will generate new unique identifiers, which can be viewed in the output.

## 🧩 Outputs

- `unique_id`: A UUID generated during Terraform execution
- `execution_signature`: A random hexadecimal identifier representing the runtime instance

## 🤔 Use Cases

- Tracking Terraform execution instances
- Debugging and logging
- Creating unique runtime markers
- Forcing configuration refreshes

## 🛡️ Security

This configuration generates random identifiers and does not interact with any external systems or create infrastructure.

## 📄 License

[Insert your preferred open-source license]

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.
