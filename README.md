# crump-tools

A collection of PowerShell scripts and configuration templates from the CrumpNet homelab.

These tools are shared as practical references — not polished products. They reflect real work done in a homelab and small enterprise environment. Use them as a starting point, not a drop-in solution.

## Structure

```
crump-tools/
├── powershell/
│   ├── active-directory/   # AD user, group, and OU management
│   ├── networking/         # DNS, DHCP, and network utilities
│   ├── monitoring/         # Health checks and alerting scripts
│   └── general/            # General purpose utilities
└── templates/
    ├── active-directory/   # OU structure and delegation templates
    ├── group-policy/       # GPO configuration references
    ├── network/            # VLAN and firewall design templates
    └── pki/                # PKI/certificate authority templates
```

## Usage

Scripts are designed for Windows PowerShell 5.1 and PowerShell 7+. Each script includes a comment block at the top describing its purpose, requirements, and usage.

Always review a script before running it in your environment. Test in a non-production environment first.

## Related

- **Site:** [crump.net](https://www.crump.net) — writeups and documentation behind these tools
- **Profile:** [joshuacrump.com](https://joshuacrump.com)

## License

MIT License — see [LICENSE](LICENSE) for details.
