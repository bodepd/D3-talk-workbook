# Overview

The compute resource allows compute to be provisioned for processes in a way that
supports both availability and supports upgrades without downtime.

# Inputs

container: container to be provisioned
memory: amount of memory to be scheduled
cpu: amount of cpu to be scheduled
health_check: scripts that runs on the local container to validate that service is healthy.
readiness_prove: script that runs on local container to validate that service has started
repicates: number of instances to run concurrently

# outputs

hostname: Each provisioned deployment gets a local hostname
