# hpc-rdma-homelab


# HPC RDMA Home Lab – Proxmox 3-Node Cluster
**Building production-grade high-performance networking skills for Supercomputing roles**

## Hardware Used (from my existing lab)
- Dell PowerEdge R720 (existing Proxmox host with live workloads – untouched)
- 2x Cisco UCS C22 M3 servers (fresh Proxmox installs)
- Onboard 1/10GbE NICs for initial cluster fabric

**Status**: In Progress (Step 1 Completion)  
**Goal**: Demonstrate hands-on RDMA/RoCE, GPUDirect, Kubernetes + NCCL/MPI experience using existing hardware (Dell PowerEdge R720 + 2x Cisco UCS C22 M3).

## Project Objectives
- Deploy 3-node Proxmox VE 9.x cluster without disrupting existing workloads
- Run baseline MPI/NCCL distributed tests
- Prepare environment for Mellanox ConnectX-5 RDMA/RoCEv2 + GPUDirect RDMA
- Document everything for future Kubernetes + GPU workloads

## Step 1 – 3-Node Proxmox Cluster (Completed Pending)

**Star this repo if you're building a similar HPC lab!**
