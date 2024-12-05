# NextBox.Neos.CCM19

> A package to integrate [CCM19](https://www.ccm19.de/) into Neos.

## Authors & Sponsors

Enes Erk - enes.erk@nextbox.dev  

## Installation

```
composer require nextbox/neos-ccm19
```

## Configuration

Configure the api-key and domain-key in Settings.yaml:

```yaml
NextBox:
  Neos:
    CCM19:
      apiKey: ''
      domainKey: ''
```

Or add the mixin to your root page:

```yaml
'Foo.Bar:RootPage':
  superTypes:
    'NextBox.Neos.CCM19:Mixin.CCM19Key': true
```
