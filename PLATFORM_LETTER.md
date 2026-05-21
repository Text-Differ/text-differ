# Security & Compliance Statement

Dear Enterprise Security Partners & IT Compliance Leads,

We are writing regarding **Text-Differ**, a text difference utility built to assist developers, editors, and legal compliance teams while ensuring strict data isolation on local workstations.

## Our Philosophy

Text-Differ is built on a single core principle: **local computation**. Text files, customer databases, intellectual property, and proprietary code bases must never leave the boundary of the local user session. Unlike web-based comparison utilities that transmit data packages to remote hosts, Text-Differ processes text entirely inside local system memory.

## Security Commitments

To ensure alignment with corporate security frameworks, Text-Differ implements these boundaries:

- **No Data Harvesting**: The application does not collect analytics telemetry, user metadata, or document filenames.
- **Bundled Dependencies**: Core libraries and npm packages are bundled with the application build to reduce reliance on external runtime resources.

## Integration Possibilities

For corporate environments, we support:
1. Integration with corporate shell commands and CLI pipelines.
2. Group policy configurations to block external network sockets completely.
3. Custom installer bundles for automated internal network distribution.

## Contact Us

If your security audit team requires detailed SOC2 reports, vulnerability disclosures, or custom enterprise installation sheets:

- Email: security@text-differ.com
- Website: [https://text-differ.com](https://text-differ.com)

Best regards,  
The Text-Differ Team
