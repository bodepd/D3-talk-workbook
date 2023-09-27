# Overview

ingress defines the rules for how a compute instance deployed from the compute service can
be routed to. It supports both path and host based routing for a set of services and
handles the dns records as well as the certificates for each service.

# inputs

dns_name: the dns record to be assigned to the load balancer

paths: a map of each path and to the local dns name that it routes to

# outputs
