# ![LOGO](logo.png) ResourceHealthMetadata API Client **flow**ground Connector

## Description

A generated **flow**ground connector for the ResourceHealthMetadata API Client API (version 2018-02-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/web-ResourceHealthMetadata/2018-02-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:24+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List all ResourceHealthMetadata for all sites in the subscription.

*Tags:* `ResourceHealthMetadata`

#### Input Parameters
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### List all ResourceHealthMetadata for all sites in the resource group in the subscription.

*Tags:* `ResourceHealthMetadata`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Gets the category of ResourceHealthMetadata to use for the given site as a collection

*Tags:* `ResourceHealthMetadata`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of web app.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Gets the category of ResourceHealthMetadata to use for the given site

*Tags:* `ResourceHealthMetadata`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of web app
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Gets the category of ResourceHealthMetadata to use for the given site as a collection

*Tags:* `ResourceHealthMetadata`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of web app.
* `slot` - _required_ - Name of web app slot. If not specified then will default to production slot.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Gets the category of ResourceHealthMetadata to use for the given site

*Tags:* `ResourceHealthMetadata`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `name` - _required_ - Name of web app
* `slot` - _required_ - Name of web app slot. If not specified then will default to production slot.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

## License

**flow**ground :- Telekom iPaaS / azure-com-web-resource-health-metadata-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
