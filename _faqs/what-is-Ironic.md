---
question: What is Ironic and how does Metal3 relate to it?
---

Ironic is a bare metal provisioner, it handles provisioning of physical machines. Metal3 exposes a part of the Ironic functionality as a Kubernetes native API via the Baremetal Operator. Ironic is not part of Metal3 but Metal3 relies on Ironic to provision the bare metal hosts.
