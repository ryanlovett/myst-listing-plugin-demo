---
title: "Maintenance reminder: Slurm scheduler software update"
description: "A scheduled update to the SLURM scheduler was performed, with careful monitoring to minimize disruption."
author: "Harper Linwood"
date: "2025-03-03"
options:
    date-modified: "2025-03-04"
keywords:
  - Ubuntu
  - Maintenance
---

::: {.callout-note}
This is a reminder for the upgrade announcement originally sent on February 19.
:::

## Announcement

We scheduled a minor software update for the SLURM scheduler, which manages both batch and JupyterHub jobs on the cluster, for Tuesday, March 4 at 1:00pm. The update was necessary to address recent security advisories and improve job scheduling efficiency.

During the maintenance window, running and queued jobs were monitored closely. While we anticipated no interruptions, we advised users to save their work and avoid submitting new jobs during the update period. The ability to submit or start new jobs was temporarily paused for up to 60 minutes.

## Update

The Slurm scheduler software update was completed successfully. The cluster resumed normal operation, and all job queues were restored. No running jobs were interrupted, and post-update monitoring showed improved scheduler responsiveness. Please contact us if you notice any issues or have questions about the update.
