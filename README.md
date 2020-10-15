# My home Kubernetes cluster managed by GitOps

![Kubernetes](https://i.imgur.com/p1RzXjQ.png)

[![Discord](https://img.shields.io/badge/discord-chat-7289DA.svg?maxAge=60&style=flat-square)](https://discord.gg/d7C9M7)    [![k3s](https://img.shields.io/badge/k3s-v1.18.8-orange?style=flat-square)](https://k3s.io/)    [![GitHub stars](https://img.shields.io/github/stars/bjw-s/k8s-gitops?color=green&style=flat-square)](https://github.com/bjw-s/k8s-gitops/stargazers)    [![GitHub issues](https://img.shields.io/github/issues/bjw-s/k8s-gitops?style=flat-square)](https://github.com/bjw-s/k8s-gitops/issues)    [![GitHub last commit](https://img.shields.io/github/last-commit/bjw-s/k8s-gitops?color=purple&style=flat-square)](https://github.com/bjw-s/k8s-gitops/commits/master) [![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white&style=flat-square)](https://github.com/pre-commit/pre-commit)

---

## Overview

Welcome to my home Kubernetes cluster.

Lots of fun (to me at least ;)) stuff can be found, poke around my [deployments](./deployments/) directory to see what my cluster is running. Feel free to open a [GitHub Issue](https://github.com/bjw-s/k8s-gitops/issues/new).

---

## Hardware

This cluster runs on the following hardware (all nodes are running bare-metal on Ubuntu 20.04):

| Device                                  | Count | OS Disk Size | Data Disk Size       | Ram  | Purpose                                          |
|-----------------------------------------|-------|--------------|----------------------|------|--------------------------------------------------|
| Lenovo ThinkCentre M93p Tiny (i5-4570T) | 1     | 250GB SSD    | N/A                  | 8GB  | k3s Master                                       |

## Community

We've got a vibrant community of folks all running various Kubernetes workloads at home. Click the Discord link above to join us!

---
## Thanks

A lot of inspiration for this repo came from the following people:
- [onedr0p/k3s-gitops](https://github.com/onedr0p/k3s-gitops)
- [billimek/k8s-gitops](https://github.com/billimek/k8s-gitops)
- [carpenike/k8s-gitops](https://github.com/carpenike/k8s-gitops)
- [dcplaya/k8s-gitops](https://github.com/dcplaya/k8s-gitops)

## Internal Wish List
- PiHole
- Grocy
- NextCloud
- UniFi MGMT
- VSCode self-hosted
- Ghidra server?
- Git tea
- EQServer
- PLONK stack
- bitwardenrs
- s4 ipfs s3 
- heimdall?
- trango?
- zerotier moon?
- slingcode
- calibre web
- duplicati
- esphome
- frigate
- node-red
