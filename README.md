# ![LOGO](logo.png) Security Center **flow**ground Connector

## Description

A generated **flow**ground connector for the Security Center API (version 2017-08-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/security-workspaceSettings/2017-08-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:55+03:00

## API Description

API spec for Microsoft.Security (Azure Security Center) resource provider

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Settings about where we should store your security data and logs. If the result is empty, it means that no custom-workspace configuration was set

*Tags:* `Workspace Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `subscriptionId` - _required_ - Azure subscription ID

### Deletes the custom workspace settings for this subscription. new VMs will report to the default workspace

*Tags:* `Workspace Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `subscriptionId` - _required_ - Azure subscription ID
* `workspaceSettingName` - _required_ - Name of the security setting

### Settings about where we should store your security data and logs. If the result is empty, it means that no custom-workspace configuration was set

*Tags:* `Workspace Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `subscriptionId` - _required_ - Azure subscription ID
* `workspaceSettingName` - _required_ - Name of the security setting

### Settings about where we should store your security data and logs

*Tags:* `Workspace Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `subscriptionId` - _required_ - Azure subscription ID
* `workspaceSettingName` - _required_ - Name of the security setting

### creating settings about where we should store your security data and logs

*Tags:* `Workspace Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `subscriptionId` - _required_ - Azure subscription ID
* `workspaceSettingName` - _required_ - Name of the security setting

## License

**flow**ground :- Telekom iPaaS / azure-com-security-workspace-settings-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
