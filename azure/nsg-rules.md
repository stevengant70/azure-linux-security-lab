# Network Security Group Rules

## Inbound Rules
- Allow SSH (TCP 22) from a single trusted public IP
- All other inbound traffic denied by default

## Rationale
Restricting SSH access minimizes attack surface and enforces least privilege at the network layer.
