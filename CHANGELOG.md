# Change log

## Unreleased

## v0.1.0-B2009009 (pre-release)

What's changed since pre-release v0.1.0-B2008005:

- General improvements:
  - Updated rule content to align with Microsoft Azure Well-Architected Framework pillars. [#23](https://github.com/microsoft/PSRule.Rules.CAF/issues/23)
  - Updated naming rules to check for recommended naming prefixes. [#29](https://github.com/microsoft/PSRule.Rules.CAF/issues/29)
    - Checks to determine if a resource name is valid are available in `PSRule.Rules.Azure`.
- Engineering:
  - Updated to PSRule v0.20.0. [#24](https://github.com/microsoft/PSRule.Rules.CAF/issues/24)
- Bug fixes:
  - Fixed Storage Account `st` prefix. [#28](https://github.com/microsoft/PSRule.Rules.CAF/issues/28)
  - Fixed Virtual Network Gateway `vgw-` prefix. [#30](https://github.com/microsoft/PSRule.Rules.CAF/issues/30)
  - Fixed Virtual Machine `vm` prefix. [#31](https://github.com/microsoft/PSRule.Rules.CAF/issues/31)
  - Fixed Load Balancer `lbe-` and `lbi-` prefixes. [#32](https://github.com/microsoft/PSRule.Rules.CAF/issues/32)
  - Fixed exclude `AzureFirewallSubnet` from `CAF.Name.Subnet`. [#27](https://github.com/microsoft/PSRule.Rules.CAF/issues/27)

## v0.1.0-B2008005 (pre-release)

What's changed since pre-release v0.1.0-B2001009:

- Bug fixes:
  - Fixed coexistence with PSRule.Rules.Azure. [#20](https://github.com/microsoft/PSRule.Rules.CAF/issues/20)

## v0.1.0-B2001009 (pre-release)

- Initial pre-release.
