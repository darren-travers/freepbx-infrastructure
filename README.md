# FreePBX Infrastructure Deployment

## Overview

This repository contains high-level deployment notes and configuration structure for a private VoIP infrastructure stack built on:

- Ubuntu 22.04 LTS (Hetzner Cloud VPS)
- FreePBX (PJSIP)
- SIP trunk provider integration
- Yealink desk phone provisioning
- Secure firewall and SSH key authentication

## Architecture

- VPS hosted in EU region
- PJSIP trunk configuration
- Outbound route management
- DID provisioning (UK + International)
- TLS/HTTPS enabled web interface
- Key-based SSH authentication only

## Objectives

- Cost-efficient VoIP routing
- International DID support
- Hardened infrastructure
- Scalable SIP trunk integration

## Status

Initial deployment completed.
SIP trunk testing in progress.
Outbound routing validation underway.
