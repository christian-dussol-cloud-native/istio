# Istio Learning Resources

> Educational repository for learning Istio: Service Mesh, Zero-Trust Security & Traffic Management

Part of **CNCF Project Focus** series, exploring cloud-native technologies in depth.

## About This Repository

This repository contains learning materials and educational examples for **Istio**, the open-source service mesh graduated by the CNCF.

**Educational focus.** Real code and examples.

### [istio-ambient-lab/](./istio-ambient-lab)

Hands-on lab to run Istio in ambient mode on a local kind cluster, one step per carousel slide, including:

- Istio 1.31.1 installation in ambient mode (no sidecars, one ztunnel per node)
- Mesh-wide mTLS with a STRICT `PeerAuthentication`
- Identity-based L4 authorization: only `service-a` may call `service-b`
- A waypoint proxy, and the policy it breaks on purpose
- A 90/10 traffic split and a request timeout with a Gateway API `HTTPRoute`
- L7 metrics for code you don't own, queried in Prometheus, from metrics to SLIs

## 📚 Learning Modules

Modules will be added progressively as part of the CNCF Project Focus series.

## Educational Content

This repository provides **learning materials and reference implementations**. Always review and adapt code to your specific requirements before using in production.

## License

This repository is licensed under Creative Commons Attribution-ShareAlike 4.0 International License.

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

## 👤 Author

[Christian Dussol](https://www.linkedin.com/in/christiandussol/)

---

**Part of CNCF Project Focus series**, Episode #6: Istio
