# Security Policy

## Reporting a Vulnerability

We take the security of Pantry Connect and the privacy of its users seriously.

If you discover a security vulnerability—whether it's a code issue, configuration risk, or something related to a potential data leak—we encourage you to **report it responsibly and privately** so we can address it promptly.

### 📧 Contact

Please report vulnerabilities by emailing:  
**[security@amazinggracepantry.org](mailto:security@amazinggracepantry.org)**

Include:
- A clear description of the issue
- Steps to reproduce (if applicable)
- Any relevant logs, screenshots, or affected code paths
- Severity or potential impact as you see it

We will acknowledge your report within **72 hours**, and provide a full response (including next steps or a resolution timeline) within **5 business days** whenever possible.

---

## 🔐 Supported Versions

We will apply security updates to the following versions:

| Version | Status        |
|---------|---------------|
| `main`  | ✅ Actively supported (stable) |
| `dev`   | ⚠️ Under development (not guaranteed secure) |

Older versions or forks are not maintained. If you're running a modified instance, we strongly encourage keeping up with security patches from `main`.

---

## 🧰 Best Practices for Self-Hosting

While Pantry Connect is open source and self-hosted, we strongly recommend that you:
- Run behind a firewall or reverse proxy (e.g., NGINX)
- Use HTTPS (with valid certificates)
- Keep PHP, MySQL, and your OS fully patched
- Limit database access and user privileges
- Change default credentials immediately upon deployment

---

## 🏅 Recognition

If you responsibly disclose a security issue, we’re happy to credit you in our release notes (unless you prefer anonymity).

Thank you for helping keep Pantry Connect safe and secure for the communities who rely on it.
