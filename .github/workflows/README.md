### **GitHub Workflows**

#### 📌 **Overview**

This directory (`.github/workflows/`) contains GitHub Actions workflow definitions that automate various tasks such as
CI/CD, releases, and repository synchronization.

#### ⚙️ **Workflows**

Below is a list of the workflows included in this repository:

| Workflow File                  | Purpose                                                           |
|--------------------------------|-------------------------------------------------------------------|
| `dockerfile-lint.yml`          | Run Hadolint to check Dockerfiles for best practices.             |
| `pulumi-deploy.yml`            | Deploy infrastructure using Pulumi.                               |
| `pulumi-destroy.yml`           | Clean up infrastructure resources using Pulumi.                   |
| `python-deps-install-test.yml` | Verify Python dependencies install for different Python versions. |
| `python-static-checks.yml`     | Run Ruff linter and formatter, and MyPy static type checks.       |
| `shellcheck.yml`               | Run [shellcheck](https://github.com/koalaman/shellcheck/).        |
| `yaml-format.yml`              | Run YAML linter tool (yamlfmt).                                   |

#### 🔄 **Workflow Categories**

The workflows can be categorized into several groups:

1. **Code Quality**
   - `python-static-checks.yml`
   - `shellcheck.yml`
   - `yaml-format.yml`
   - `dockerfile-lint.yml`

2. **Dependency Management**
   - `python-deps-install-test.yml`
   - `license-check.yml`

3. **Infrastructure Management**
   - `pulumi-deploy.yml`
   - `pulumi-destroy.yml`
