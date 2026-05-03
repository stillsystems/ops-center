# <picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/stillsystems/.github/main/brand/logo.png"><img alt="Still Systems" src="https://raw.githubusercontent.com/stillsystems/.github/main/brand/logo.png" width="32" height="32"></picture> Still Systems Ops Center

**Centralized infrastructure monitoring and incident management.**

This repository serves as the global monitoring hub for the **Still Systems** organization. It is where automated CI/CD failures, security alerts, and infrastructure incidents are logged and tracked.

## 🚨 Incident Management

When a critical failure occurs in any Still Systems repository (e.g., a failed CI run for a core tool), an automated incident report is created here.

### Incident Labels
- `incident`: General infrastructure or workflow failure.
- `ci-failure`: Automated CI/CD pipeline breakage.
- `security-alert`: Potential vulnerability or secret exposure.
- `blocker`: Critical issue preventing releases or distribution.

## 🛠️ Global Monitoring

The monitoring is powered by the [Global Failure Notification](https://github.com/stillsystems/.github/blob/main/.github/workflows/failure-notify.yml) workflow located in our organizational `.github` repository.

## 🤝 Support

If you encounter an issue that isn't automatically logged, please refer to our [Global Support Guidelines](https://github.com/stillsystems/.github/blob/main/SUPPORT.md).

---
🧱 **Still Systems** — Tools engineered for real-world conditions.
