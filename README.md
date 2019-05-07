# ![LOGO](logo.png) ComputeDiskAdminManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ComputeDiskAdminManagementClient API (version 2018-07-30-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-Disks/2018-07-30-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:27+03:00

## API Description

The Admin Compute Disk Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of disks.

*Tags:* `Disks`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `userSubscriptionId` - _optional_ - User Subscription Id which the resource belongs to.
* `status` - _optional_ - The parameters of disk state.
* `sharePath` - _optional_ - The source share which the resource belongs to.
* `count` - _optional_ - The maximum number of disks to return.
* `start` - _optional_ - The start index of disks in query.
* `api-version` - _required_ - Client API Version.

### Returns the disk.

*Tags:* `Disks`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `DiskId` - _required_ - The disk guid as identity.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-disks-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
