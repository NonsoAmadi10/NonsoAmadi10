# Chinonso Amadi

## Crypto Infrastructure Security Engineer — Bitcoin · Ethereum · Solana

---

I secure the infrastructure that moves money on-chain — not smart contracts, but the nodes, validators, key management systems, and production clusters beneath them. 7+ years building and hardening Bitcoin and Lightning infrastructure at scale.

### What I build

**Bitcoin & Lightning Security**
- Hardware enclave deployments for Bitcoin custody (AWS Nitro)
- LND hardening — watchtowers, channel backup automation, macaroon ACLs
- Multisig coordination, PSBT workflows, key ceremony design
- Stratum V2 protocol benchmarking and tooling

**Multi-Chain Validator & Node Infrastructure**
- Ethereum validator operations — sentry architecture, slashing protection, Web3Signer
- Solana validator hardening — RPC isolation, vote monitoring, leader slot security
- Production Kubernetes clusters (EKS, bare-metal) — 99.99%+ uptime
- Full observability: Prometheus, Grafana, Loki, Tempo, Thanos

**Key Management & Custody**
- HSM integration for transaction signing (CloudHSM, YubiHSM)
- MPC and threshold signature architectures (FROST, TSS)
- Hot/warm/cold wallet infrastructure with policy engines
- Compliance-ready platforms: PCI-DSS, SOC2, ISO 27001

**Bridge & Cross-Chain Security**
- Bridge monitoring, anomaly detection, circuit breaker patterns
- On-chain forensics and incident response
- Hack analysis: infrastructure controls that prevent the next Ronin/Wormhole

### Featured projects

| Project | What it does |
|---------|-------------|
| [`terraform-aws-bitcoin-enclave-node`](https://github.com/NonsoAmadi10/terraform-aws-bitcoin-enclave-node) | Terraform modules for hardened Bitcoin nodes on AWS Nitro Enclaves |
| [`Heimdall`](https://github.com/NonsoAmadi10/Heimdall) | Real-time monitoring for Bitcoin & Lightning node operators |
| [`psbt-coordinator`](https://github.com/NonsoAmadi10/psbt-coordinator) | 2-of-3 multisig PSBT coordinator in Rust |
| [`mempool-fee-analysis`](https://github.com/NonsoAmadi10/mempool-fee-analysis) | Mempool-based fee estimation API and CLI |
| [`zwis`](https://github.com/NonsoAmadi10/zwis) | In-memory cache with LRU, LFU, and ARC eviction policies |
| [`abobi`](https://github.com/NonsoAmadi10/abobi) | CLI that converts env files into Kubernetes base64-encoded secrets |

### Stack

`Go` · `Rust` · `Python` · `Terraform` · `Kubernetes` · `AWS` · `Docker` · `Helm` · `ArgoCD` · `Prometheus` · `Bitcoin Core` · `LND` · `Geth` · `Lighthouse` · `Solana`

### Certifications

- CKA — Certified Kubernetes Administrator
- AWS Solutions Architect Associate
- AWS Data Engineer Associate

---

<a href="https://www.linkedin.com/in/nonso-amadi/">LinkedIn</a> · <a href="https://twitter.com/jackhoudini__">Twitter</a> · <a href="https://medium.com/@jackhoudini">Blog</a> · nonsoamadi@aol.com
