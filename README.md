# AT&T Developer Hub (at-t-developer-hub)
The AT&T Developer Hub provides access to cutting-edge network APIs including 5G, edge computing, and CAMARA industry-standard APIs. The Network API Accelerator Program offers early adopters pre-release, invite-only access to network capabilities spanning device status, SIM swap detection, number verification, quality of service on demand, network insights, and mobility threat detection. AT&T's network APIs enable developers to build advanced applications leveraging the U.S. mobile network for authentication, fraud prevention, performance optimization, and security.

**URL:** [https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - 5G, Network APIs, CAMARA, Connectivity, Telecommunications, Edge Computing, Device Status, SIM Swap

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-04-19

## APIs

### AT&T Network Insights API
Delivers performance metrics and device-level network data, providing developers with insights into network conditions, signal quality, and performance indicators for connected devices on the AT&T network.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

#### Tags:

 - Network Performance, Metrics, 5G, Monitoring

#### Properties

- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)
- [OpenAPI](openapi/at-t-developer-hub-network-insights-api.yaml)

### AT&T Mobility Threat and Anomaly Detection API
Uses machine learning to identify threats and unusual activity on mobile devices on the AT&T network. Provides real-time threat detection signals to applications for enhanced security, fraud prevention, and anomaly detection across subscriber devices.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

#### Tags:

 - Security, Fraud Detection, Machine Learning, Anomaly Detection, Threat Intelligence

#### Properties

- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)
- [OpenAPI](openapi/at-t-developer-hub-mobility-threat-anomaly-detection-api.yaml)

### AT&T SIM Swap API
CAMARA-standard API that checks when SIM cards associated with mobile numbers have changed. Enables applications to strengthen authentication flows and detect SIM swap fraud by querying AT&T's network for recent SIM card changes on a subscriber's number.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

#### Tags:

 - SIM Swap, Authentication, Fraud Prevention, CAMARA, Security

#### Properties

- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)
- [OpenAPI](openapi/at-t-developer-hub-sim-swap-api.yaml)

### AT&T Device Status API
CAMARA-standard API that checks the connectivity status of user equipment, including roaming information. Enables applications to determine if a device is reachable, connected, and whether it is roaming on a partner network.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

#### Tags:

 - Device Status, Connectivity, Roaming, CAMARA, 5G

#### Properties

- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)
- [OpenAPI](openapi/at-t-developer-hub-device-status-api.yaml)

### AT&T Quality on Demand API
CAMARA-standard Quality of Service on Demand (QoD) API that temporarily enhances Quality of Service on 5G PDU sessions. Enables applications to request prioritized network throughput, reduced latency, or guaranteed bandwidth for time-sensitive operations.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

#### Tags:

 - Quality of Service, QoS, 5G, CAMARA, Network Slicing, Latency

#### Properties

- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)
- [OpenAPI](openapi/at-t-developer-hub-quality-on-demand-api.yaml)

### AT&T Number Verification API
CAMARA-standard API enabling seamless device authentication via the mobile network. Verifies that a device is currently using a specific phone number without requiring the user to enter an OTP.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

#### Tags:

 - Number Verification, Authentication, Identity, CAMARA, Mobile

#### Properties

- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)
- [OpenAPI](openapi/at-t-developer-hub-number-verification-api.yaml)

## Common Properties

- [Website](https://www.att.com/)
- [Portal](https://developer.att.com/s/)
- [DeveloperPortal](https://devex-web.att.com/developer-hub/)
- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)
- [SignUp](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)
- [TermsOfService](https://www.att.com/gen/general?pid=11561)
- [PrivacyPolicy](https://www.att.com/gen/privacy-policy?pid=2506)
- [GitHubOrganization](https://github.com/attdevsupport)

## Features

| Name | Description |
|------|-------------|
| CAMARA Industry-Standard APIs | Implements GSMA CAMARA open-source standard APIs including SIM Swap, Device Status, Number Verification, and Quality on Demand for cross-carrier interoperability. |
| Network API Accelerator Program | Invite-only early access program for developers to trial pre-release 5G network APIs and influence future network capability development. |
| 5G Network Capabilities | Exposes AT&T's 5G network intelligence including QoS on demand, network performance insights, and device connectivity status. |
| Fraud Prevention Network Signals | Network-based fraud signals including SIM swap detection, number verification, and mobility threat detection to strengthen app security. |

## Use Cases

| Name | Description |
|------|-------------|
| SIM Swap Fraud Prevention | Detect recent SIM card changes to prevent account takeover attacks and strengthen multi-factor authentication flows. |
| Frictionless Mobile Authentication | Verify device phone numbers silently via the network without OTP codes, reducing authentication friction in mobile apps. |
| 5G Quality of Service Optimization | Request guaranteed bandwidth or low latency for real-time applications like video conferencing, AR/VR, and industrial IoT. |
| Device Connectivity Monitoring | Monitor device connectivity and roaming status to trigger location-aware application behaviors. |
| Threat Detection and Security | Leverage AT&T network ML-based threat signals to detect anomalous device behavior and security incidents. |

## Integrations

| Name | Description |
|------|-------------|
| Aduna Network API Platform | AT&T's partnership with Aduna provides standardized access to AT&T 5G Network APIs with cross-carrier interoperability for all three major U.S. carriers. |
| Vonage (Ericsson) | Collaboration with Vonage to bring AT&T CAMARA network APIs to communications platform developers. |
| GSMA CAMARA | Member of GSMA's CAMARA open-source project defining standardized telco network APIs for cross-operator portability. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AT&T Network Insights API](openapi/at-t-developer-hub-network-insights-api.yaml)
- [AT&T Mobility Threat and Anomaly Detection API](openapi/at-t-developer-hub-mobility-threat-anomaly-detection-api.yaml)
- [AT&T SIM Swap API](openapi/at-t-developer-hub-sim-swap-api.yaml)
- [AT&T Device Status API](openapi/at-t-developer-hub-device-status-api.yaml)
- [AT&T Quality on Demand API](openapi/at-t-developer-hub-quality-on-demand-api.yaml)
- [AT&T Number Verification API](openapi/at-t-developer-hub-number-verification-api.yaml)

### JSON Schema

- [SIM Swap Check Request](json-schema/sim-swap-api-sim-swap-check-request-schema.json)
- [SIM Swap Check Response](json-schema/sim-swap-api-sim-swap-check-response-schema.json)
- [Device Connectivity Status](json-schema/device-status-api-device-connectivity-status-schema.json)
- [Device Roaming Status](json-schema/device-status-api-device-roaming-status-schema.json)
- [Session Info](json-schema/quality-on-demand-api-session-info-schema.json)
- [Network Metrics](json-schema/network-insights-api-network-metrics-schema.json)
- [Threat Assessment](json-schema/mobility-threat-anomaly-detection-api-threat-assessment-schema.json)
- *(and 16 additional schema files)*

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [AT&T SIM Swap API](capabilities/shared/sim-swap-api.yaml) — 2 operations for SIM swap fraud detection
- [AT&T Device Status API](capabilities/shared/device-status-api.yaml) — 2 operations for device connectivity and roaming
- [AT&T Number Verification API](capabilities/shared/number-verification-api.yaml) — 1 operation for silent phone verification
- [AT&T Quality on Demand API](capabilities/shared/quality-on-demand-api.yaml) — 4 operations for 5G QoS session management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [AT&T Network Security](capabilities/network-security.yaml) | SIM Swap API, Number Verification API | 3 | Security Developer, Identity Developer |
| [AT&T Network Performance](capabilities/network-performance.yaml) | Device Status API, Quality on Demand API | 6 | App Developer, IoT Engineer |

## Vocabulary

- [AT&T Developer Hub Vocabulary](vocabulary/at-t-developer-hub-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 8 actions, 2 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [AT&T Developer Hub Spectral Rules](rules/at-t-developer-hub-spectral-rules.yml) — 26 rules across 10 categories enforcing AT&T CAMARA network API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
