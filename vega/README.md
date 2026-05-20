# Vega HPC

Vega is the CFAL lab's on-premise High Performance Computing (HPC) cluster, used for large-scale simulations and data processing tasks. This section covers everything you need to get started and run jobs on Vega.

If you are new to Vega, start with [What is Vega?](./getting-started/01_what_is_vega.md) and work through the getting started pages in order before moving on to software-specific guides.

---

## Getting Started

| Page | Description |
|------|-------------|
| [What is Vega?](./getting-started/01_what_is_vega.md) | Overview of HPC, when to use Vega, and hardware summary |
| [Accessing Vega](./getting-started/02_access_setup.md) | Connecting via VS Code and setting up SSH keys |
| [Vega Basics](./getting-started/03_vega_basics.md) | File system layout, node types, job scheduler, and modules |
| [Resource Planning](./getting-started/04_resource_planning.md) | How to estimate memory and core requirements |
| [Job Submission](./getting-started/05_job_submission.md) | Writing job scripts, submitting, and monitoring jobs |
| [GPU Computing](./getting-started/06_gpu_computing.md) | When and how to use Vega's GPU nodes |

---

## Software

### Star-CCM+
| Page | Description |
|------|-------------|
| [Single Case](./software/starccm/01_single_case.md) | Running a single simulation |
| [Design Manager](./software/starccm/02_design_manager.md) | Running parameter sweeps and multi-case studies |

### Coming Soon
- ANSYS Fluent
- OpenFOAM

---

## Reference

| Page | Description |
|------|-------------|
| [Vega Hardware](./reference/vega_hardware.md) | Full hardware and software specs, per-user limits, queues |
| [Job Script Directives](./reference/job_script_directives.md) | Complete PBS directives and environment variables |
| [Troubleshooting](./reference/troubleshooting.md) | Common issues and fixes (coming soon) |