**Project Title:** Real-Time Apache Security Monitoring Dashboard

**Description:**

In today's data-driven environment, raw server logs are a goldmine of security and operational intelligence, but they are often underutilized due to their volume and complexity. The challenge is to transform these logs into a clear, actionable, and real-time "single pane of glass" that can empower a Security Operations Center (SOC) to proactively identify and respond to threats.

To solve this, I developed a comprehensive security monitoring dashboard in Splunk Enterprise to analyze and visualize JSON-formatted Apache access logs. This dashboard serves as a centralized command center for threat hunting and operational health monitoring.

**Key Features & Accomplishments:**

*   **Actionable KPIs:** Developed at-a-glance metrics for total requests, successful responses, and, most critically, 4xx (client-side) and 5xx (server-side) error rates. A spike in 4xx errors can immediately indicate scanning or forced browsing attacks, while a surge in 5xx errors can signal application-layer DoS attacks.
*   **Proactive Threat Hunting:** Created visualizations for "Top Requested URIs" and "Top User IPs" to instantly flag anomalies. This allows an analyst to spot scanning for common vulnerabilities (e.g., `wp-admin.php`, `.env`) and identify the source IPs of potential brute-force or DoS attacks.
*   **Geographic Threat Intelligence:** Implemented a dynamic choropleth map by leveraging Splunk's `iplocation` and `geom` commands. This provides immediate situational awareness by visualizing the geographic origin of web traffic, making it easy to spot anomalous activity from unexpected regions.

This project showcases the ability to turn raw, unstructured data into a strategic asset for cybersecurity defense.

**Skills Demonstrated:**

*   Splunk Enterprise & Splunk Processing Language (SPL)
*   Security Operations (SOC) & Threat Hunting
*   Log Analysis (JSON/Apache)
*   Data Visualization & Dashboarding
*   Cybersecurity Monitoring & Anomaly Detection
*   Incident Response Enablement