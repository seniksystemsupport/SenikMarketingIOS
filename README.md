# Senik Marketing iOS reconstruction

Native SwiftUI reconstruction of the Senik Marketing Android app based on `marketing-release-V2.3.apk`.

Current implemented scaffold:
- Dynamic per-customer server IP and port, blank by default
- Persisted local server settings
- Connection test
- RTL SwiftUI root flow
- Initial login request/response models
- Initial API client
- GitHub Actions macOS build that packages an unsigned IPA for later signing/sideloading

Reconstruction targets from APK:
- authentication endpoint/contract verification
- branches and app settings
- customers and account turnover
- products/groups/prices/stores
- invoices / sales / return / proforma / reserve
- factor agents / settlement agents
- offline database and sync behavior
