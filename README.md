# omniORB Builds

This repository provides precompiled, platform-optimized builds of
[omniORB](https://omniorb.sourceforge.io/), a robust and
high-performance implementation of the
[Common Object Request Broker Architecture (CORBA)](https://www.corba.org/index.htm),
with support for both C++ and Python language bindings.

Rather than serving as a source code repository for omniORB itself, this
project functions as an automated build and packaging pipeline. It
leverages GitHub Actions as the continuous integration backend to
compile omniORB across a well-defined build matrix covering multiple CPU
architectures, Linux distributions, and Python interpreter versions.

Each workflow is carefully designed to ensure reproducibility,
traceability, and compatibility across diverse deployment environments.
Upon successful execution, the resulting artifacts—including native
binaries and Python bindings—are automatically assembled, versioned, and
published under the repository’s [Releases](../../releases) section,
making them readily available for downstream integration, validation,
and deployment.

## Supported Architectures

The following CPU architectures are targeted for build support:

- [ ] [x86-64 (AMD64)](https://en.wikipedia.org/wiki/X86-64)
- ARM:
  - [ ] ARMv6 (32-bit)
  - [ ] ARMv7-A (32-bit)
  - ARMv8-A:
    - [ ] AArch32 (32-bit)
    - [ ] [AArch64 (64-bit)](https://en.wikipedia.org/wiki/AArch64)

## Supported Operating Systems

Builds are planned for the following Linux distributions, organized by
packaging format:

- **`.deb`-based distributions**:
  - [ ] Debian
  - [ ] Ubuntu

- **`.rpm`-based distributions**:
  - [ ] CentOS
  - [ ] Fedora
  - [ ] Red Hat Enterprise Linux (RHEL)

## Supported Python Versions

Python bindings will be provided for the following interpreter versions:

- [ ] 2.7 (legacy support)
- [ ] 3.5
- [ ] 3.6
- [ ] 3.7
- [ ] 3.8
- [ ] 3.9
- [ ] 3.10
- [ ] 3.11
- [ ] 3.12
- [ ] 3.13
