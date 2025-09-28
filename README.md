# Wazuh Knowledge Center

[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
[![Community](https://img.shields.io/badge/community-join-blue.svg)](https://wazuh.com/community/)
[![Documentation](https://img.shields.io/badge/docs-official-green.svg)](https://documentation.wazuh.com/)

A comprehensive, community-driven knowledge center for the Wazuh security platform. This repository consolidates documentation, guides, examples, and resources from across the Wazuh ecosystem into a single, searchable, and well-organized knowledge base.

## About Wazuh

Wazuh is a free and open source security platform that unifies XDR and SIEM protection for endpoints and cloud workloads. The platform provides comprehensive threat prevention, detection, and response capabilities across on-premises, virtualized, containerized, and cloud-based environments.

## Repository Overview

This knowledge center contains **1,020+ documentation files** collected from **21 official Wazuh repositories**, organized into a structured format that supports both learning paths and reference usage. The content covers everything from basic installation to advanced enterprise deployment scenarios.

### Key Features

- **Comprehensive Coverage**: Complete documentation from all major Wazuh components
- **Structured Organization**: Intuitive navigation supporting multiple user journeys
- **Community-Driven**: Open contribution model with clear guidelines
- **Search Optimized**: Organized for discoverability through GitHub's search functionality
- **Cross-Referenced**: Extensive linking between related topics and components
- **Multi-Audience**: Content appropriate for users, administrators, and developers

## Quick Navigation

### 🚀 Getting Started
- **[Platform Overview](getting-started/platform-overview/)** - Architecture, capabilities, and use cases
- **[Quickstart Guide](getting-started/quickstart/)** - Rapid deployment for evaluation
- **[Proof of Concept](getting-started/proof-of-concept/)** - POC deployment scenarios

### 📦 Installation & Deployment
- **[Installation Guide](installation-guide/)** - Comprehensive installation procedures
- **[Deployment Options](deployment-options/)** - Docker, Kubernetes, VMs, and automation
- **[System Requirements](installation-guide/system-requirements/)** - Hardware and software prerequisites

### 👥 User Guides
- **[User Manual](user-manual/)** - Operational procedures and configuration
- **[Dashboard Usage](user-manual/dashboard-usage/)** - UI navigation and visualization
- **[Agent Management](user-manual/agents/)** - Agent deployment and configuration

### ☁️ Cloud & Integration
- **[Cloud Security](cloud-security/)** - AWS, Azure, GCP, and GitHub monitoring
- **[Integrations](integrations/)** - SIEM, SOAR, ticketing, and threat intelligence
- **[API Reference](api-reference/)** - Complete API documentation

### 🛠️ Development & Customization
- **[Development Guide](development/)** - API usage, plugin development, custom rules
- **[Dashboard Customization](dashboard/)** - UI configuration and plugin management
- **[Examples](examples/)** - Code samples and configuration templates

### 🏢 Enterprise Features
- **[Server Management](server/)** - Server configuration and cluster management
- **[Agent Deployment](agent/)** - Enterprise agent management
- **[Compliance](user-manual/compliance/)** - PCI DSS, GDPR, HIPAA configurations

## Content Organization

### By User Type

**Security Analysts**
- [Dashboard Usage](user-manual/dashboard-usage/) → [Alert Investigation](user-manual/dashboard-usage/alerts-management.md) → [Threat Hunting](examples/threat-hunting/)

**System Administrators**
- [Installation Guide](installation-guide/) → [Deployment Options](deployment-options/) → [Server Management](server/)

**Developers**
- [Development Guide](development/) → [API Reference](api-reference/) → [Plugin Development](development/plugins/)

**Compliance Officers**
- [Compliance Guide](user-manual/compliance/) → [Reporting](user-manual/dashboard-usage/reporting.md) → [Audit Configuration](examples/compliance/)

### By Deployment Scenario

**Single Node Deployment**
- [Quickstart](getting-started/quickstart/single-node.md) → [Basic Installation](installation-guide/) → [Initial Configuration](user-manual/)

**Enterprise Cluster**
- [Multi-Node Setup](getting-started/quickstart/multi-node.md) → [Cluster Installation](installation-guide/) → [High Availability](deployment-options/)

**Cloud Deployment**
- [Cloud Quickstart](getting-started/quickstart/cloud-deployment.md) → [Cloud Security](cloud-security/) → [Auto-scaling](deployment-options/kubernetes/)

**Container Orchestration**
- [Docker Deployment](deployment-options/docker/) → [Kubernetes](deployment-options/kubernetes/) → [Production Scaling](deployment-options/kubernetes/scaling.md)

## Repository Statistics

| Category | Content | Description |
|----------|---------|-------------|
| **Documentation Files** | 1,020+ | Comprehensive technical documentation |
| **Code Examples** | 200+ | Functional configuration and code samples |
| **Integration Guides** | 50+ | Third-party platform connectivity |
| **Deployment Patterns** | 25+ | Infrastructure deployment strategies |
| **API Endpoints** | 100+ | Complete API reference documentation |
| **Use Cases** | 30+ | Real-world implementation scenarios |

## Contributing

We welcome contributions from the Wazuh community! This knowledge center thrives on community input and collaborative improvement.

### How to Contribute

1. **Fork the Repository** - Create your own copy for modifications
2. **Choose Your Contribution** - Documentation improvements, new examples, or corrections
3. **Follow Guidelines** - Review our [Contributing Guide](CONTRIBUTING.md)
4. **Submit Pull Request** - Detailed description of changes and improvements
5. **Community Review** - Collaborate with maintainers and community members

### Contribution Areas

- **Documentation Enhancement** - Improve existing guides and references
- **Example Development** - Create practical configuration examples
- **Translation** - Multi-language documentation support
- **Integration Guides** - New platform integration documentation
- **Best Practices** - Share operational experience and recommendations

## Community and Support

### Official Channels

- **[Official Documentation](https://documentation.wazuh.com/)** - Primary Wazuh documentation
- **[Community Forum](https://wazuh.com/community/)** - Community discussions and support
- **[Slack Channel](https://wazuh.com/community/join-us-on-slack/)** - Real-time community chat
- **[Mailing List](https://groups.google.com/forum/#!forum/wazuh)** - Email-based community discussions

### Knowledge Center Specific

- **[Issues](../../issues)** - Report problems or request improvements
- **[Discussions](../../discussions)** - Community conversations about content
- **[Pull Requests](../../pulls)** - Active contributions and reviews

## License and Legal

This knowledge center is licensed under the GNU General Public License v2.0, consistent with the Wazuh project licensing. All content respects the original licensing of source repositories while providing community value through organization and accessibility.

### Attribution

This repository consolidates and organizes content from official Wazuh repositories maintained by the Wazuh team. Original content remains attributed to respective authors and maintainers. The knowledge center adds value through organization, cross-referencing, and community curation.

### Disclaimer

This community knowledge center is not officially maintained by Wazuh, Inc. For official support and enterprise services, please contact Wazuh directly through their official channels.

## Repository Maintenance

### Update Schedule

- **Weekly**: New content integration from official repositories
- **Monthly**: Structural improvements and navigation enhancements
- **Quarterly**: Comprehensive review and reorganization as needed

### Quality Standards

- **Accuracy**: All content verified against official sources
- **Consistency**: Standardized formatting and organization patterns
- **Accessibility**: Clear navigation and multiple discovery paths
- **Community Focus**: Responsive to community needs and feedback

---

**Start your Wazuh journey**: [Getting Started Guide](getting-started/) | **Need help?**: [Community Support](community/) | **Want to contribute?**: [Contributing Guide](CONTRIBUTING.md)
