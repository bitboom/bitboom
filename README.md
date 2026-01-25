# Sangwan Kwon

Staff Software Engineer  
Security & Privacy Team, AI Platform Center  
Samsung Electronics  
sangwan.kwon@samsung.com · bitboom9@gmail.com

-----

## Professional Summary

System security engineer with 10+ years of experience building
security-critical software across embedded security processors,
mobile devices, and cloud infrastructure.

Specialized in confidential computing and Rust-based systems programming;
built a hypervisor now adopted as a Linux Foundation
Confidential Computing Consortium (CCC) project.

Currently designing a hardened Cloud OS for Private Cloud Compute,
enabling secure AI inference with hardware isolation.

-----

## Core Technical Expertise

- **Confidential Computing**
  - Designing a **hardened Cloud OS for Private Cloud Compute** using **Intel TDX**
  - Built **Rust-based Realm Management Monitor (RMM)** for Arm CCA adopted as a CCC Project
  - Contributed **Arm CCA backend support** in CCC projects for cross-platform confidential computing APIs
- **System & Kernel Security**
  - Designed and implemented embedded secure OS for Samsung Knox Vault’s hardware-isolated security processor,
    completing technology transfer to business division
  - Designed security middleware for Tizen platforms including unified security monitors,
    TrustZone-based authentication, and per-application namespace isolation for SSL trust anchors
- **Rust Systems Programming**
  - Applied Rust across the full spectrum from bare-metal no_std to full-featured environments
  - Developed a compiler-level tool to detect unsafe code at the HIR stage
    and used Miri-based validation to improve auditability and reduce unsafe usage
  - Maintain CCC open-source project, reviewing and evaluating external contributions

-----

## Selected Projects

### Vigilo — Hardened Cloud OS for Private Cloud Compute on Intel TDX (2025 – Present)

- Architecting a hardened Cloud OS leveraging **Intel TDX**
  for Private Cloud Compute
- Defining **OS-level enforcement** to achieve on-device-equivalent privacy
- Planned for open-source release

### Islet — On-Device Confidential Computing (2022 – 2024)

- Core architect and developer of Arm CCA-based
  confidential computing platform, implementing Rust-based
  **Realm Management Monitor (RMM)** managing realm lifecycle
- Built a **Confidential Application SDK** providing
  **Attestation** and **Sealing**
- Contributed the Rust-based **RMM** to the
  Linux Foundation’s **Confidential Computing Consortium (CCC)**
  as a project deliverable
- Collaborated with VMware on **Certifier Framework**,
  implementing **Arm CCA backend support** for cross-platform confidential computing APIs
- Demonstrated at Confidential Computing Summit 2023

### Camellia — Rust-based Secure OS for Security Processors (2020 – 2022)

- Designed and implemented **Camellia**, a Rust-based secure OS kernel
  for Samsung Knox Vault’s security processor in a **no_std** environment
- Built a **type-safe RPC framework** for secure inter-process communication
- Developed a Rust tool to trace unsafe code at the HIR stage,
  minimizing unsafe code usage
- Completed technology transfer to business division,
  meeting production requirements for **stability, performance, and reliability**
  in mass-produced devices

### Tizen — Security Middleware (2015 – 2020)

- Contributed to **commercialization** of Mobile, TV, and Wearable products
- Designed unified security monitor for device policy management
- Developed TrustZone-based authentication framework
- Implemented Modern C++ RPC framework for secure client-server method invocation
- Maintained SSL trust anchors and application signature validation

-----

## Open Source & Patents

- **Islet Project** — Maintainer
- **Certifier Framework** — Contributor
- **Patents:** Confidential Computing (KR 2024),
  Key Management (KR 2020, US 2022),
  Data Protection (KR 2020),
  Container Security (KR 2019, US 2020)

-----

## Education

**M.S., Computer Science** | Yonsei University, South Korea | 2014 – 2017  
**B.S., Computer Science** | Kookmin University, South Korea | 2007 – 2014

-----

## Links

- Islet Project (GitHub):
  https://github.com/islet-project/islet
- Confidential Computing Consortium (Projects):
  https://confidentialcomputing.io/projects/current-projects/
- Certifier Framework:
  https://github.com/ccc-certifier-framework/certifier-framework-for-confidential-computing
- The Register (CCC/Standards):
  https://www.theregister.com/2023/06/30/confidential_computing_standards/
- SiliconANGLE (VMware-Samsung):
  https://siliconangle.com/2023/06/29/vmware-partners-samsung-amd-risc-v-accelerate-confidential-computing/