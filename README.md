# CSPService
Programmatically create CSP Trusted Site settings in Lightning components via tooling API.

Requires sfdc-lax https://github.com/ruslan-kurchenko/sfdc-lax

and Httpex https://github.com/metacursion/Httpex

and Remote Site Setting for your own org.

See example below on for how to use:
```
component
    .find('CSPService')
    .create({
      "DeveloperName":"myWhiteListedDomain",
      "isActive":true,
      "endpointUrl":"https://my.domain.com"
      })
```

WARNING:
See also:

License: BSD
