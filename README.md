# CVAT Local Setup — No Docker

Complete guide to running CVAT locally without Docker or Kubernetes.

## What this solves
Standard CVAT requires Docker + Nuclio for AI-assisted annotation.
This setup replaces that with lightweight local Python services,
making it fully offline and air-gapped compatible.

## What's inside
- Full CVAT local deployment guide
- Nuclio mock service (replaces Docker-based function discovery)
- YOLO inference bridge (local auto-annotation without orchestration)
- Shape-to-track script (converts frame-wise polyshapes → continuous polygon tracks for video)

## Who this is for
Anyone running CVAT on secure/offline infrastructure,
or who just wants a simpler setup without Docker overhead.

## Setup
See `cvat_guide.pdf` for full step-by-step instructions.

## Author
Pranav Shinde — AI/CV Engineer
[LinkedIn](https://linkedin.com/in/pranaavshinde) | [X](https://x.com/Pranaav2412)
