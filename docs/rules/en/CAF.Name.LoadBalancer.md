---
pillar: Operational Excellence
category: Resource naming
online version: https://github.com/microsoft/PSRule.Rules.CAF/blob/main/docs/rules/en/CAF.Name.LoadBalancer.md
---

# Use standard load balancer names

## SYNOPSIS

Load balancer names should use a standard prefix.

## DESCRIPTION

An effective naming convention allows operators to quickly identify resource type, associated workload,
deployment environment and Azure region.

For load balancers, the Cloud Adoption Framework recommends using the `lbi-`, and `lbe-` prefix.
Use of different prefixes depends on the intended usage of the load balancer.

Requirements for load balancers names:

- At least 1 character, but no more than 80.
- Can include alphanumeric, underscore, hyphen, period characters.
- Can only start with a letter or number, and end with a letter, number or underscore.
- Load balancer names must be unique within a resource group.

## RECOMMENDATION

Consider creating load balancers with a standard name.
Additionally consider using Azure Policy to only permit creation using a standard naming convention.

## NOTES

This rule does not check if load balancer names are unique.

To configure this rule:

- Override the `CAF_LoadBalancerPrefix` configuration value with an array of allowed prefixes.

## LINKS

- [Recommended naming and tagging conventions](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/naming-and-tagging)
- [Azure Well-Architected Framework](https://docs.microsoft.com/en-gb/azure/architecture/framework/devops/app-design#tagging-and-resource-naming)
- [Naming rules and restrictions for Azure resources](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/resource-name-rules)
