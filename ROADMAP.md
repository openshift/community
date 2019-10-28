# OKD 4 Roadmap

## General Guidelines
* Use Ignition Spec v3
* Be able to bootstrap from and build on Fedora CoreOS (FCoS)
* Avoid unnecessary divergence in OKD branches of projects within the OpenShift organization
* Align and standardize metrics, reboot and other applicable APIs in RHEL CoreOS (OCP base OS) and FCoS whenever sensible and feasible
* Platforms that are supported by both FCOS and OCP will be supported by OKD

## Phase 0: Short Term (MVP)
**Goal:** Enable the community to install, test and try out a preview version of OKD

* Ensure Installer can serve Ignition Spec v3
* Ensure Installer is able to bootstrap a cluster from an FCoS base
* Ensure pivot from standard FCoS to machine-os-content works
* Ensure machine-config-operator (MCO) supports Ignition Spec v3
* Create OpenShift CI that injects kubelet and cri-o into machine-os-content based on standard FCoS image that is publicly accessible (no auth required)
* Use os-containers (container-embedded OSTree-commits, same model as in OCP) for update payload delivery

## Phase 1: Mid Term (GA)
**Goal:** Release a first stable version for consumption by the community which is closely oriented at OCP

* Stabilize by increased manual and CI testing (including for upgrades)
* Enable Libvirt as a platform and work towards OKD Code Ready Containers
* Document the installation process

## Phase 2: Long Term (post GA)
**Goal:** Enable more use-cases and setups; make OKD a superset of OCP

* Discussions on switching out kubelet/cri-o versions
* Discussion on Zincati (FCoS Update Agent) integration as an alternative means of update payload delivery
* Investigate possible UX improvements, e.g:
    * Add helpers for retrieving Let’s Encrypt/ACME certificates on nodes
    * Optionally include openshift-acme and/or cert-manager to automatically retrieve ACME certificates for routes/ingresses on the cluster
    * Enable customization of OKD, e.g. by adding or removing certain components
* Explore supporting more base OSes
* Explore supporting more platforms (e.g. IoT, more cloud providers)
* Continuously update roadmap to incorporate community feedback
