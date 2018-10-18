---
title: Create Encrypted PVCs
weight: 5
---

## Volume encryption

This document describes how to provision an encrypted volume using Kubernetes and Portworx. For more information on encryption, [click here](/reference/cli/data-volumes/encrypted-volumes/).

Before you start using PVC encryption, you need to setup a secrets provider to store your secret keys and configure Portworx to use it. [Click here](/reference/key-management/).

There are a couple of ways you can create an encrypted Portworx volume in Kubernetes:

1. [Encryption using StorageClass](/portworx-install-with-kubernetes/storage-operations/create-pvcs/storage-class-encryption)
2. [Encryption using PVC](/portworx-install-with-kubernetes/storage-operations/create-pvcs/pvc-encryption)