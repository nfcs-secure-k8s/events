---
hide:
  - navigation
  - toc
---

# NFCS Secure Kubernetes Block storage Workshops

Welcome to the NFCS Secure Kubernetes workshop and event site.

This site provides information about workshops, technical demonstrations,
presentations and project resources relating to secure Kubernetes storage,
LUKS encryption, federated identity and trusted research environments.

[View upcoming workshop](workshops/secure-kubernetes-workshop.md){ .md-button .md-button--primary }

[View the agenda](agenda.md){ .md-button }

## Upcoming event

| Date         | Event                      | Location                                   | Format               | Details                                                  |
| ------------ | -------------------------- | ------------------------------------------ | -------------------- | -------------------------------------------------------- |
| 20 July 2026 | Secure Kubernetes Workshop | University of Cambridge - WestHub (room D) | In person and online | [View workshop](workshops/secure-kubernetes-workshop.md) |

<!-- <h2>Workshop themes</h2>

<div class="workshop-grid">

  <div class="workshop-card">
    <div class="workshop-title">
      <span class="twemoji">
        :material-kubernetes:
      </span>
      <strong>Secure Kubernetes</strong>
    </div>
    <p>Kubernetes security controls for sensitive research environments.</p>
  </div>

  <div class="workshop-card">
    <div class="workshop-title">
      <span class="twemoji">
        :material-lock:
      </span>
      <strong>Storage encryption</strong>
    </div>
    <p>Automated LUKS encryption for Kubernetes block storage.</p>
  </div>

  <div class="workshop-card">
    <div class="workshop-title">
      <span class="twemoji">
        :material-key:
      </span>
      <strong>Key management</strong>
    </div>
    <p>Institution-controlled keys using HashiCorp Vault.</p>
  </div>

  <div class="workshop-card">
    <div class="workshop-title">
      <span class="twemoji">
        :material-account-key:
      </span>
      <strong>Federated identity</strong>
    </div>
    <p>OIDC-based authentication and tenant-specific access control.</p>
  </div>

</div> -->

## Workshop themes

<div class="workshop-grid" markdown>

<div class="workshop-card" markdown>

### :material-kubernetes: Secure Kubernetes

Kubernetes security controls for sensitive research environments.

</div>

<div class="workshop-card" markdown>

### :material-lock: Storage encryption

Automated LUKS encryption for Kubernetes block storage.

</div>

<div class="workshop-card" markdown>

### :material-key: Key management

Institution-controlled keys using HashiCorp Vault.

</div>

<div class="workshop-card" markdown>

### :material-account-key: Federated identity

OIDC-based authentication and tenant-specific access control.

</div>

</div>

## About the project

The project investigates methods for automating encryption of Kubernetes
block storage in Trusted Research Environments.

The approaches include:

- a Kubernetes Operator-based encryption model;
- transparent encryption through a CSI driver;
- integration with HashiCorp Vault;
- federated access using OIDC;
- institution-controlled key ownership.
