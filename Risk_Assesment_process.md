# Step 2: Risk Assessment Process

## Asset Identification
| Asset Type | Description | Importance |
|------------|-------------|------------|
| Customer Database | 500K PII records | Critical |
| AWS EC2 Instances | 50 production servers | High |
| Employee Laptops | 200 devices | High |
| Web Application | Customer portal | Critical |

## Threat Identification
| Asset | Threats |
|-------|---------|
| Database | Ransomware, SQL injection |
| AWS EC2 | DDoS, misconfiguration |
| Laptops | Phishing, malware |
| Web App | OWASP Top 10 |

## Vulnerability Assessment
| Asset | Vulnerabilities |
|-------|-----------------|
| Database | Unencrypted backups |
| AWS EC2 | Public S3 buckets |
| Laptops | No endpoint protection |
| Web App | XSS, SQL injection |

## Risk Analysis Matrix
| Risk | Likelihood | Impact | Priority |
|------|------------|--------|----------|
| Ransomware | High | Critical | CRITICAL |
| DDoS | Medium | High | HIGH |
| Phishing | High | Medium | HIGH |
