# Mansveld Expotech Engineering
This GitHub organization hosts **work-related projects** for Mansveld Expotech Infra B.V. It centralizes codebases, documentation, and tools accross different enviroments and machines.

---

## Purpose
- Centralize and standardize work projects
- Facilitate collaboration between team members and machines
- Maintain version control, documentation, and security best practices

---

## Repository Structure
- **Poject Repositories**: Named after the project or feature (e.g., `mx-riggingplan-check`, `fte-dashboard`).
- **Shared Tools**: Prefixed with `tool-` (e.g., `tool-ci-scripts`).
- **Documentation**: Prefixed iwth `docs-` (e.g., `docs-onboarding`).

---
## Getting Started
1. **Clone a Repository**:
   ```bash
   git clone git@github.com:Mansveld-Expotech-Engineering/[repo-name].git
   ```
2. **Set Up Environment**
   - Use .env.example for environment variables
   - Install dependencies with `uv pip install -r pyproject.toml`

3. **Contribute**
   - Fork the repository, create a feature branch and submit a pull request.

---
## Workflow & Guidelines
- **Branching**: Use feature/, bugfix/ or release/ prefixes.
- **Commits**: Follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).
- **Pull Requests**: Require at least 1 approval before merging.
- **Code Standards**: Use PEP 8 to start.
---
## Security & Access
- **Access**: Restricted to team members. Request access via Bart.
- **Secrets**: Never hardcore API Keys. Use .env files.
- **Complience**: Follow company data protection and security policies.
---
## Support
- **Issues**: Open a GitHub issue in the relevant repository.
