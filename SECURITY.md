# Security Policy

## Reporting a Vulnerability

We take security seriously at Think-Zone. If you discover a security vulnerability in any of our repositories, please report it responsibly.

**Please do not open a public GitHub issue for security vulnerabilities.**

### How to Report

1. **GitHub Private Reporting** — Use the [Security Advisories](https://github.com/think-zone/creator-os/security/advisories/new) feature on the affected repository to submit a private report.
2. 2. **What to include:**
   3.    - A description of the vulnerability
         -    - Steps to reproduce the issue
              -    - Potential impact
                   -    - Any suggested fixes (optional)
                    
                        - ### What to Expect
                    
                        - - We will acknowledge your report within **72 hours**
                          - - We will investigate and work on a fix, aiming to resolve critical issues within **7 days**
                            - - We will credit you in the release notes (unless you prefer to remain anonymous)
                             
                              - ## Scope
                             
                              - This policy applies to all public repositories under the `think-zone` organization:
                             
                              - - [`think-zone/creator-os`](https://github.com/think-zone/creator-os)
                                - - [`think-zone/cognitive-mcp`](https://github.com/think-zone/cognitive-mcp)
                                 
                                  - ## Known Security Practices
                                 
                                  - - All secrets are stored in encrypted vaults — never committed to source
                                    - - Secret scanning is enabled on all public repositories
                                      - - Dependabot alerts are enabled for dependency vulnerability monitoring
                                        - - Branch protection rules are enforced on `main`
                                         
                                          - ## Out of Scope
                                         
                                          - - Vulnerabilities in third-party dependencies (please report to the upstream maintainer)
                                            - - Theoretical vulnerabilities without a proof of concept
                                              - - Social engineering attacks
