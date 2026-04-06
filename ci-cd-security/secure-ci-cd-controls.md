# Secure CI/CD Control Example

## Objective
Ensure CI/CD pipelines are secured, controlled, and auditable to prevent unauthorized code changes, deployments, or misuse.

## Control Expectations

- Access to CI/CD pipelines is restricted based on role and least privilege
- Pipeline changes require peer review and approval (e.g., pull requests)
- Secrets are not hardcoded and are managed securely
- Build and deployment activity is logged and monitored
- Production deployments are traceable to approved changes
- Separation of duties is enforced where appropriate

## Evidence Examples

- GitHub Actions workflow configurations
- Pull request approval history
- Deployment logs
- Repository access control settings
- Secrets management configurations

## Why This Matters

In modern environments, CI/CD pipelines are a critical control point for both security and compliance. Securing pipelines ensures that code integrity, deployment processes, and auditability are maintained without slowing down engineering velocity.
