# ![LOGO](logo.png) MonitorManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the MonitorManagementClient API (version 2018-01-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-metricDefinitions_API/2018-01-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:27+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists the metric definitions for the resource.

*Tags:* `MetricDefinitions`

#### Input Parameters
* `resourceUri` - _required_ - The identifier of the resource.
* `api-version` - _required_ - Client Api Version.
* `metricnamespace` - _optional_ - Metric namespace to query metric definitions for.

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-metric-definitions-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
