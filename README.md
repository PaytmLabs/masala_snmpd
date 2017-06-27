# masala_snmpd

This is a component of the [masala toolkit](https://github.com/PaytmLabs/masala).

This is a [wrapper cookbook](http://blog.vialstudios.com/the-environment-cookbook-pattern/#thewrappercookbook) for providing recipes for a simplified configuration for net-snmp.

## Supported Platforms

The platforms supported are:
- Centos 6.7+ / Centos 7.1+
- Ubuntu 14.04 LTS (And future LTS releases)
- Debian 8.2+

## Attributes

Please see the documentation for the cookbooks included by masala_snmpd. (See [metadata.rb](https://github.com/PaytmLabs/masala_snmpd/blob/develop/metadata.rb) and [Berksfile](https://github.com/PaytmLabs/masala_snmpd/blob/develop/Berksfile) files)

This cookbook does not add any attributes of it's own. It *does* override the listen address default to only include localhost. This can be overriden.

## Usage

### masala_snmpd::default

Include `masala_snmpd` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[masala_snmpd::default]"
  ]
}
```

## License, authors, and how to contribute

See:
- [LICENSE](https://github.com/PaytmLabs/masala_snmpd/blob/develop/LICENSE)
- [MAINTAINERS.md](https://github.com/PaytmLabs/masala_snmpd/blob/develop/MAINTAINERS.md)
- [CONTRIBUTING.md](https://github.com/PaytmLabs/masala_snmpd/blob/develop/CONTRIBUTING.md)

