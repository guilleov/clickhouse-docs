---
title: 'GCP Private Networking Setup'
slug: /cloud/reference/byoc/onboarding/network-gcp
sidebar_label: 'GCP Private Networking Setup'
keywords: ['BYOC', 'cloud', 'bring your own cloud', 'vpc peering', 'gcp', 'private service connect']
description: 'Deploy ClickHouse on your own cloud infrastructure'
doc_type: 'reference'
---

ClickHouse BYOC on GCP supports two private connection options including VPC Peering and Private Service Connect. Traffic flows entirely within the GCP network, never traversing the public internet.

## Setup VPC Peering {#gcp-vpc-peering}

To create or delete VPC peering for ClickHouse BYOC, follow the steps:

<VerticalStepper headerLevel="h3">

## Setup Private Service Connect {#gcp-psc}

GCP Private Service Connect provides secure, private connectivity to your ClickHouse BYOC services without requiring VPC peering or internet gateways.
