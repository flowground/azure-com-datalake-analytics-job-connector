# ![LOGO](logo.png) DataLakeAnalyticsJobManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the DataLakeAnalyticsJobManagementClient API (version 2017-09-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/datalake-analytics-job/2017-09-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:59+03:00

## API Description

Creates an Azure Data Lake Analytics job client.

## Authorization

This API does not require authorization.

## Actions

### Builds (compiles) the specified job in the specified Data Lake Analytics account for job correctness and validation.

*Tags:* `Job`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Lists the jobs, if any, associated with the specified Data Lake Analytics account. The response includes a link to the next page of results, if any.

*Tags:* `Job`

#### Input Parameters
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Gets the job information for the specified job ID.

*Tags:* `Job`

#### Input Parameters
* `jobIdentity` - _required_ - JobInfo ID.
* `api-version` - _required_ - Client Api Version.

### Updates the job information for the specified job ID. (Only for use internally with Scope job type.)

*Tags:* `Job`

#### Input Parameters
* `jobIdentity` - _required_ - Job identifier. Uniquely identifies the job across all jobs submitted to the service.
* `api-version` - _required_ - Client Api Version.

### Submits a job to the specified Data Lake Analytics account.

*Tags:* `Job`

#### Input Parameters
* `jobIdentity` - _required_ - Job identifier. Uniquely identifies the job across all jobs submitted to the service.
* `api-version` - _required_ - Client Api Version.

### Cancels the running job specified by the job ID.

*Tags:* `Job`

#### Input Parameters
* `jobIdentity` - _required_ - Job identifier. Uniquely identifies the job across all jobs submitted to the service.
* `api-version` - _required_ - Client Api Version.

### Gets the job debug data information specified by the job ID.

*Tags:* `Job`

#### Input Parameters
* `jobIdentity` - _required_ - Job identifier. Uniquely identifies the job across all jobs submitted to the service.
* `api-version` - _required_ - Client Api Version.

### Gets statistics of the specified job.

*Tags:* `Job`

#### Input Parameters
* `jobIdentity` - _required_ - Job Information ID.
* `api-version` - _required_ - Client Api Version.

### Pauses the specified job and places it back in the job queue, behind other jobs of equal or higher importance, based on priority. (Only for use internally with Scope job type.)

*Tags:* `Job`

#### Input Parameters
* `jobIdentity` - _required_ - Job identifier. Uniquely identifies the job across all jobs submitted to the service.
* `api-version` - _required_ - Client Api Version.

### Lists all pipelines.

*Tags:* `Pipeline`

#### Input Parameters
* `startDateTime` - _optional_ - The start date for when to get the list of pipelines. The startDateTime and endDateTime can be no more than 30 days apart.
* `endDateTime` - _optional_ - The end date for when to get the list of pipelines. The startDateTime and endDateTime can be no more than 30 days apart.
* `api-version` - _required_ - Client Api Version.

### Gets the Pipeline information for the specified pipeline ID.

*Tags:* `Pipeline`

#### Input Parameters
* `pipelineIdentity` - _required_ - Pipeline ID.
* `startDateTime` - _optional_ - The start date for when to get the pipeline and aggregate its data. The startDateTime and endDateTime can be no more than 30 days apart.
* `endDateTime` - _optional_ - The end date for when to get the pipeline and aggregate its data. The startDateTime and endDateTime can be no more than 30 days apart.
* `api-version` - _required_ - Client Api Version.

### Lists all recurrences.

*Tags:* `Recurrence`

#### Input Parameters
* `startDateTime` - _optional_ - The start date for when to get the list of recurrences. The startDateTime and endDateTime can be no more than 30 days apart.
* `endDateTime` - _optional_ - The end date for when to get the list of recurrences. The startDateTime and endDateTime can be no more than 30 days apart.
* `api-version` - _required_ - Client Api Version.

### Gets the recurrence information for the specified recurrence ID.

*Tags:* `Recurrence`

#### Input Parameters
* `recurrenceIdentity` - _required_ - Recurrence ID.
* `startDateTime` - _optional_ - The start date for when to get the recurrence and aggregate its data. The startDateTime and endDateTime can be no more than 30 days apart.
* `endDateTime` - _optional_ - The end date for when to get recurrence and aggregate its data. The startDateTime and endDateTime can be no more than 30 days apart.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-datalake-analytics-job-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
