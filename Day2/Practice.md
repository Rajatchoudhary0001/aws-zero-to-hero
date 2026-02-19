# AWS WAF (Web Application Firewall)
AWS WAF (Web Application Firewall) is a managed security service that helps safeguard web applications from common exploits and attacks. It works by inspecting incoming HTTP(S) requests and applying rules you define to allow, block, or monitor traffic.

## How It Works
- **Web ACLs (Access Control Lists):** Define rules to allow, block, or count requests.
- **Association with Resources:** Attach ACLs to CloudFront distributions, Application Load Balancers (ALB), or API Gateway endpoints.
- **Traffic Inspection:** Incoming HTTP(S) requests are evaluated against rules before reaching the application.
- **Actions:** Requests can be allowed, blocked, or monitored.

## Protection Capabilities
- **Mitigates common attacks:**
  - SQL injection
  - Cross-site scripting (XSS)
  - Malicious bots and scrapers
- **Rate-based rules:** Limit requests from specific IPs to prevent denial-of-service attempts.
- **Geo-blocking:** Restrict traffic from certain countries or regions.
- **Integration with AWS Shield:** Adds DDoS protection.

## Benefits
- **Customizable security:** Tailor rules to your application’s needs.
- **Scalable:** Protects applications globally via CloudFront or regionally via ALB/API Gateway.
- **Cost-effective:** Pay only for rules and requests inspected.

---

## Summary
AWS WAF acts as a **gatekeeper** for your applications—filtering out malicious traffic while letting legitimate requests through, ensuring both security and availability.
