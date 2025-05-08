---
title: "Downtime notice: Cluster node OS upgrade"
description: "We are upgrading the operating system on most systems, with careful planning to minimize user impact."
author: "Sage Whitaker"
date: "2025-03-21"
keywords:
  - Ubuntu
  - Maintenance
---

We will be performing operating system upgrades on all of our compute servers during the upcoming spring break. The upgrades will occur in batches from Monday, March 24, through Thursday, March 27, starting each morning at approximately 8:30am. We will begin with the least active nodes to reduce disruption to ongoing research.

Your home and scratch directories will not be affected, however /tmp and /var/tmp on each machine will be wiped. /data partitions, which exist on a small number of systems, will not be impacted. We have coordinated with research groups to ensure critical jobs are not interrupted and have provided guidance on checkpointing and job resubmission.

We will place reservations on the systems to be upgraded about 72 hours in advance. If you currently have or plan to start jobs that you expect to run into next week, please ensure that your code can resume from where it left off if interrupted. For jobs starting before the upgrade, we recommend setting a time limit of no more than 72 hours. Our team will be available throughout the upgrade period to assist with any issues.
