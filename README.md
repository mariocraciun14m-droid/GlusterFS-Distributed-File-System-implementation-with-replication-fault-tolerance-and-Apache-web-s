# glusterfs
glusterfs assignment
# GlusterFS Distributed File System Assignment

## Project Overview

This project demonstrates the deployment of a distributed file system using GlusterFS within a Linux virtual machine environment.

The system was built using:

- Ubuntu 64-bit as a storage node
- Linux Mint as a storage node and web server
- Kali Linux as a client machine

The aim of this project was to configure shared storage, implement replication, test fault tolerance, and integrate the storage system with an Apache web server.

---

## System Architecture

| Machine | Role | IP Address |
|---|---|---|
| Ubuntu 64-bit | GlusterFS storage node | 192.168.206.131 |
| Linux Mint | GlusterFS storage node + Apache web server | 192.168.206.130 |
| Kali Linux | Client system | DHCP / same network |

---

## GlusterFS Configuration

GlusterFS was installed on Ubuntu and Linux Mint. Both machines were connected as peers and configured to use a replicated volume.

The volume used was: `gv0`


