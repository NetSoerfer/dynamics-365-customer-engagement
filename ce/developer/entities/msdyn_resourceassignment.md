---
title: "msdyn_resourceassignment Entity Reference (Developer Guide for Dynamics 365 Customer Engagement)| MicrosoftDocs"
description: "Includes schema information and supported messages for the msdyn_resourceassignment entity."
ms.date: 10/31/2017
ms.service: "crm-online"
ms.topic: "reference"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: 3948cc48-07c8-7f60-0608-71c37158ad7c
author: "JimDaly"
ms.author: "jdaly"
manager: "jdaly"
---
# msdyn_resourceassignment Entity Reference

[!INCLUDE[](../../includes/cc_applies_to_update_9_0_0.md)]

Entity used to keep track of resource assignment header information  on tasks.

**Added by**: Project Service Automation Solution<br />

## Messages

|Message|Web API Operation|SDK Assembly|
|-|-|-|
|Assign|PATCH [*org URI*]/api/data/v9.0/msdyn_resourceassignments(*msdyn_resourceassignmentid*)<br />[Update](../webapi/update-delete-entities-using-web-api.md#basic-update) `ownerid` property.|<xref:Microsoft.Crm.Sdk.Messages.AssignRequest>|
|Create|POST [*org URI*]/api/data/v9.0/msdyn_resourceassignments<br />See [Create](../webapi/create-entity-web-api.md)|<xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*>|
|Delete|DELETE [*org URI*]/api/data/v9.0/msdyn_resourceassignments(*msdyn_resourceassignmentid*)<br />See [Delete](../webapi/update-delete-entities-using-web-api.md#basic-delete)|<xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Delete*>|
|GrantAccess|<xref href="Microsoft.Dynamics.CRM.GrantAccess?text=GrantAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.GrantAccessRequest>|
|IsValidStateTransition|<xref href="Microsoft.Dynamics.CRM.IsValidStateTransition?text=IsValidStateTransition Function" />|<xref:Microsoft.Crm.Sdk.Messages.IsValidStateTransitionRequest>|
|ModifyAccess|<xref href="Microsoft.Dynamics.CRM.ModifyAccess?text=ModifyAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.ModifyAccessRequest>|
|msdyn_ResourceAssignmentDetailUpdate|<xref href="Microsoft.Dynamics.CRM.msdyn_ResourceAssignmentDetailUpdate?text=msdyn_ResourceAssignmentDetailUpdate Action" />|Type generated by CrmSvcUtil.exe or use <xref:Microsoft.Xrm.Sdk.OrganizationRequest> setting the required parameters for the message. |
|Retrieve|GET [*org URI*]/api/data/v9.0/msdyn_resourceassignments(*msdyn_resourceassignmentid*)<br />See [Retrieve](../webapi/retrieve-entity-using-web-api.md)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Retrieve*>|
|RetrieveMultiple|GET [*org URI*]/api/data/v9.0/msdyn_resourceassignments<br />See [Query Data](../webapi/query-data-web-api.md)|<xref:Microsoft.Xrm.Sdk.Messages.RetrieveMultipleRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.RetrieveMultiple*>|
|RetrievePrincipalAccess|<xref href="Microsoft.Dynamics.CRM.RetrievePrincipalAccess?text=RetrievePrincipalAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrievePrincipalAccessRequest>|
|RetrieveSharedPrincipalsAndAccess|<xref href="Microsoft.Dynamics.CRM.RetrieveSharedPrincipalsAndAccess?text=RetrieveSharedPrincipalsAndAccess Function" />|<xref:Microsoft.Crm.Sdk.Messages.RetrieveSharedPrincipalsAndAccessRequest>|
|RevokeAccess|<xref href="Microsoft.Dynamics.CRM.RevokeAccess?text=RevokeAccess Action" />|<xref:Microsoft.Crm.Sdk.Messages.RevokeAccessRequest>|
|SetState|PATCH [*org URI*]/api/data/v9.0/msdyn_resourceassignments(*msdyn_resourceassignmentid*)<br />[Update](../webapi/update-delete-entities-using-web-api.md#basic-update) `statecode` and `statuscode` properties.|<xref:Microsoft.Crm.Sdk.Messages.SetStateRequest>|
|Update|PATCH [*org URI*]/api/data/v9.0/msdyn_resourceassignments(*msdyn_resourceassignmentid*)<br />See [Update](../webapi/update-delete-entities-using-web-api.md#basic-update)|<xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> or <br /><xref:Microsoft.Xrm.Sdk.IOrganizationService.Update*>|

## Properties

**DisplayName**: Resource Assignment<br />
**DisplayCollectionName**: Resource Assignments<br />
**SchemaName**: msdyn_resourceassignment<br />
**CollectionSchemaName**: msdyn_resourceassignments<br />
**LogicalName**: msdyn_resourceassignment<br />
**LogicalCollectionName**: msdyn_resourceassignments<br />
**EntitySetName**: msdyn_resourceassignments<br />
**PrimaryIdAttribute**: msdyn_resourceassignmentid<br />
**PrimaryNameAttribute**: msdyn_name<br />
**OwnershipType**: UserOwned<br />
**IsBPFEntity**: False<br />
<a name="writable-attributes"></a>

## Writable attributes

These attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [msdyn_bookableresourceid](#BKMK_msdyn_bookableresourceid)
- [msdyn_bookingstatusid](#BKMK_msdyn_bookingstatusid)
- [msdyn_CommitType](#BKMK_msdyn_CommitType)
- [msdyn_fromdate](#BKMK_msdyn_fromdate)
- [msdyn_hours](#BKMK_msdyn_hours)
- [msdyn_msprojectclientid](#BKMK_msdyn_msprojectclientid)
- [msdyn_name](#BKMK_msdyn_name)
- [msdyn_plannedwork](#BKMK_msdyn_plannedwork)
- [msdyn_projectid](#BKMK_msdyn_projectid)
- [msdyn_projectteamid](#BKMK_msdyn_projectteamid)
- [msdyn_resourceassignmentId](#BKMK_msdyn_resourceassignmentId)
- [msdyn_taskid](#BKMK_msdyn_taskid)
- [msdyn_todate](#BKMK_msdyn_todate)
- [msdyn_userresourceid](#BKMK_msdyn_userresourceid)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [OwnerId](#BKMK_OwnerId)
- [OwnerIdType](#BKMK_OwnerIdType)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)


### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

**Description**: Sequence number of the import that created this record.<br />
**DisplayName**: Import Sequence Number<br />
**LogicalName**: importsequencenumber<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**IsValidForUpdate**: False<br />
**Type**: Integer<br />
**Format**: None<br />
**MaxValue**: 2147483647<br />
**MinValue**: -2147483648


### <a name="BKMK_msdyn_bookableresourceid"></a> msdyn_bookableresourceid

**Description**: Shows the resource.<br />
**DisplayName**: Bookable Resource<br />
**LogicalName**: msdyn_bookableresourceid<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: bookableresource


### <a name="BKMK_msdyn_bookingstatusid"></a> msdyn_bookingstatusid

**Description**: Booking Status<br />
**DisplayName**: Booking Status<br />
**LogicalName**: msdyn_bookingstatusid<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: bookingstatus


### <a name="BKMK_msdyn_CommitType"></a> msdyn_CommitType

**Description**: Select the commitment type of the assignment (hard or soft).<br />
**DisplayName**: Commit Type<br />
**LogicalName**: msdyn_committype<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: ApplicationRequired<br />
**Type**: Picklist<br />
**Options**:

- **Value**: 192350000 **Label**: None
- **Value**: 192350001 **Label**: Hard Book
- **Value**: 192350002 **Label**: Soft Book
- **Value**: 192350003 **Label**: Proposed
- **Value**: 192350004 **Label**: Canceled



### <a name="BKMK_msdyn_fromdate"></a> msdyn_fromdate

**Description**: Enter the date a resource is assigned from.<br />
**DisplayName**: From Date<br />
**LogicalName**: msdyn_fromdate<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: ApplicationRequired<br />
**Type**: DateTime<br />
**DateTimeBehavior**: UserLocal<br />
**Format**: DateOnly


### <a name="BKMK_msdyn_hours"></a> msdyn_hours

**Description**: Enter the number of hours for which a resource is assigned.<br />
**DisplayName**: Hours<br />
**LogicalName**: msdyn_hours<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Decimal<br />
**MaxValue**: 100000000000<br />
**MinValue**: -100000000000<br />
**Precision**: 2


### <a name="BKMK_msdyn_msprojectclientid"></a> msdyn_msprojectclientid

**Description**: id for resource assignment in ms project<br />
**DisplayName**: MS Project Client Id<br />
**LogicalName**: msdyn_msprojectclientid<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_msdyn_name"></a> msdyn_name

**Description**: Type the name of the custom entity.<br />
**DisplayName**: Name<br />
**LogicalName**: msdyn_name<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: ApplicationRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_msdyn_plannedwork"></a> msdyn_plannedwork

**Description**: Serialized planned work schedule for assignmed resource<br />
**DisplayName**: Planned Work<br />
**LogicalName**: msdyn_plannedwork<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Memo<br />
**Format**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 1048576


### <a name="BKMK_msdyn_projectid"></a> msdyn_projectid

**Description**: Select the project for which the resource is assigned.<br />
**DisplayName**: Project<br />
**LogicalName**: msdyn_projectid<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: msdyn_project


### <a name="BKMK_msdyn_projectteamid"></a> msdyn_projectteamid

**Description**: Unique identifier for Project Team Member associated with Resource Assignment.<br />
**DisplayName**: Project Team<br />
**LogicalName**: msdyn_projectteamid<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: msdyn_projectteam


### <a name="BKMK_msdyn_resourceassignmentId"></a> msdyn_resourceassignmentId

**Description**: Unique identifier for entity instances<br />
**DisplayName**: Resource Assignment<br />
**LogicalName**: msdyn_resourceassignmentid<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**IsValidForUpdate**: False<br />
**Type**: Uniqueidentifier<br />


### <a name="BKMK_msdyn_taskid"></a> msdyn_taskid

**Description**: Select the task for which the resource is assigned to.<br />
**DisplayName**: Task<br />
**LogicalName**: msdyn_taskid<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: msdyn_projecttask


### <a name="BKMK_msdyn_todate"></a> msdyn_todate

**Description**: Enter the end date until which a resource is assigned.<br />
**DisplayName**: To Date<br />
**LogicalName**: msdyn_todate<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: ApplicationRequired<br />
**Type**: DateTime<br />
**DateTimeBehavior**: UserLocal<br />
**Format**: DateOnly


### <a name="BKMK_msdyn_userresourceid"></a> msdyn_userresourceid

**Description**: Select the user whose capacity is assigned.<br />
**DisplayName**: Resource<br />
**LogicalName**: msdyn_userresourceid<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: 


### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

**Description**: Date and time that the record was migrated.<br />
**DisplayName**: Record Created On<br />
**LogicalName**: overriddencreatedon<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**IsValidForUpdate**: False<br />
**Type**: DateTime<br />
**DateTimeBehavior**: UserLocal<br />
**Format**: DateOnly


### <a name="BKMK_OwnerId"></a> OwnerId

**Description**: Owner Id<br />
**DisplayName**: Owner<br />
**LogicalName**: ownerid<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: Owner<br />
**Targets**: systemuser,team


### <a name="BKMK_OwnerIdType"></a> OwnerIdType

**Description**: Owner Id Type<br />
**DisplayName**: <br />
**LogicalName**: owneridtype<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: EntityName<br />


### <a name="BKMK_statecode"></a> statecode

**Description**: Status of the Resource Assignment<br />
**DisplayName**: Status<br />
**LogicalName**: statecode<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**IsValidForCreate**: False<br />
**Type**: State<br />
**Options**:

- **Value**: 0 **Label**: Active **DefaultStatus**: 1 **InvariantName**: Active
- **Value**: 1 **Label**: Inactive **DefaultStatus**: 2 **InvariantName**: Inactive



### <a name="BKMK_statuscode"></a> statuscode

**Description**: Reason for the status of the Resource Assignment<br />
**DisplayName**: Status Reason<br />
**LogicalName**: statuscode<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Status<br />
**Options**:

- **Value**: 1 **Label**: Active **State**: 0
- **Value**: 2 **Label**: Inactive **State**: 1



### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

**Description**: For internal use only.<br />
**DisplayName**: Time Zone Rule Version Number<br />
**LogicalName**: timezoneruleversionnumber<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Integer<br />
**Format**: None<br />
**MaxValue**: 2147483647<br />
**MinValue**: -1


### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

**Description**: Time zone code that was in use when the record was created.<br />
**DisplayName**: UTC Conversion Time Zone Code<br />
**LogicalName**: utcconversiontimezonecode<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Integer<br />
**Format**: None<br />
**MaxValue**: 2147483647<br />
**MinValue**: -1

<a name="read-only-attributes"></a>
## Read-only attributes
These attributes return false for both **IsValidForCreate** or **IsValidForUpdate**. Listed by **SchemaName**.

- [CreatedBy](#BKMK_CreatedBy)
- [CreatedByName](#BKMK_CreatedByName)
- [CreatedByYomiName](#BKMK_CreatedByYomiName)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [CreatedOnBehalfByName](#BKMK_CreatedOnBehalfByName)
- [CreatedOnBehalfByYomiName](#BKMK_CreatedOnBehalfByYomiName)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedByName](#BKMK_ModifiedByName)
- [ModifiedByYomiName](#BKMK_ModifiedByYomiName)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [ModifiedOnBehalfByName](#BKMK_ModifiedOnBehalfByName)
- [ModifiedOnBehalfByYomiName](#BKMK_ModifiedOnBehalfByYomiName)
- [msdyn_bookableresourceidName](#BKMK_msdyn_bookableresourceidName)
- [msdyn_bookingstatusidName](#BKMK_msdyn_bookingstatusidName)
- [msdyn_projectidName](#BKMK_msdyn_projectidName)
- [msdyn_projectteamidName](#BKMK_msdyn_projectteamidName)
- [msdyn_taskidName](#BKMK_msdyn_taskidName)
- [OwnerIdName](#BKMK_OwnerIdName)
- [OwnerIdYomiName](#BKMK_OwnerIdYomiName)
- [OwningBusinessUnit](#BKMK_OwningBusinessUnit)
- [OwningTeam](#BKMK_OwningTeam)
- [OwningUser](#BKMK_OwningUser)
- [VersionNumber](#BKMK_VersionNumber)


### <a name="BKMK_CreatedBy"></a> CreatedBy

**Description**: Unique identifier of the user who created the record.<br />
**DisplayName**: Created By<br />
**LogicalName**: createdby<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: systemuser


### <a name="BKMK_CreatedByName"></a> CreatedByName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: createdbyname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_CreatedByYomiName"></a> CreatedByYomiName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: createdbyyominame<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_CreatedOn"></a> CreatedOn

**Description**: Date and time when the record was created.<br />
**DisplayName**: Created On<br />
**LogicalName**: createdon<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: DateTime<br />
**DateTimeBehavior**: UserLocal<br />
**Format**: DateAndTime


### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

**Description**: Unique identifier of the delegate user who created the record.<br />
**DisplayName**: Created By (Delegate)<br />
**LogicalName**: createdonbehalfby<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: systemuser


### <a name="BKMK_CreatedOnBehalfByName"></a> CreatedOnBehalfByName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: createdonbehalfbyname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_CreatedOnBehalfByYomiName"></a> CreatedOnBehalfByYomiName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: createdonbehalfbyyominame<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_ModifiedBy"></a> ModifiedBy

**Description**: Unique identifier of the user who modified the record.<br />
**DisplayName**: Modified By<br />
**LogicalName**: modifiedby<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: systemuser


### <a name="BKMK_ModifiedByName"></a> ModifiedByName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: modifiedbyname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_ModifiedByYomiName"></a> ModifiedByYomiName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: modifiedbyyominame<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_ModifiedOn"></a> ModifiedOn

**Description**: Date and time when the record was modified.<br />
**DisplayName**: Modified On<br />
**LogicalName**: modifiedon<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: DateTime<br />
**DateTimeBehavior**: UserLocal<br />
**Format**: DateAndTime


### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

**Description**: Unique identifier of the delegate user who modified the record.<br />
**DisplayName**: Modified By (Delegate)<br />
**LogicalName**: modifiedonbehalfby<br />
**IsValidForForm**: True<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: systemuser


### <a name="BKMK_ModifiedOnBehalfByName"></a> ModifiedOnBehalfByName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: modifiedonbehalfbyname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_ModifiedOnBehalfByYomiName"></a> ModifiedOnBehalfByYomiName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: modifiedonbehalfbyyominame<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_msdyn_bookableresourceidName"></a> msdyn_bookableresourceidName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: msdyn_bookableresourceidname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_msdyn_bookingstatusidName"></a> msdyn_bookingstatusidName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: msdyn_bookingstatusidname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_msdyn_projectidName"></a> msdyn_projectidName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: msdyn_projectidname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 200


### <a name="BKMK_msdyn_projectteamidName"></a> msdyn_projectteamidName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: msdyn_projectteamidname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_msdyn_taskidName"></a> msdyn_taskidName

**Description**: <br />
**DisplayName**: <br />
**LogicalName**: msdyn_taskidname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 450


### <a name="BKMK_OwnerIdName"></a> OwnerIdName

**Description**: Name of the owner<br />
**DisplayName**: <br />
**LogicalName**: owneridname<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_OwnerIdYomiName"></a> OwnerIdYomiName

**Description**: Yomi name of the owner<br />
**DisplayName**: <br />
**LogicalName**: owneridyominame<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: SystemRequired<br />
**Type**: String<br />
**FormatName**: Text<br />
**IsLocalizable**: False<br />
**MaxLength**: 100


### <a name="BKMK_OwningBusinessUnit"></a> OwningBusinessUnit

**Description**: Unique identifier for the business unit that owns the record<br />
**DisplayName**: Owning Business Unit<br />
**LogicalName**: owningbusinessunit<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: businessunit


### <a name="BKMK_OwningTeam"></a> OwningTeam

**Description**: Unique identifier for the team that owns the record.<br />
**DisplayName**: Owning Team<br />
**LogicalName**: owningteam<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: team


### <a name="BKMK_OwningUser"></a> OwningUser

**Description**: Unique identifier for the user that owns the record.<br />
**DisplayName**: Owning User<br />
**LogicalName**: owninguser<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: Lookup<br />
**Targets**: systemuser


### <a name="BKMK_VersionNumber"></a> VersionNumber

**Description**: Version Number<br />
**DisplayName**: Version Number<br />
**LogicalName**: versionnumber<br />
**IsValidForForm**: False<br />
**IsValidForRead**: True<br />
**RequiredLevel**: None<br />
**Type**: BigInt<br />
**MaxValue**: 9223372036854775807<br />
**MinValue**: -9223372036854775808<br />

<a name="onetomany"></a>

## One-To-Many Relationships

Listed by **SchemaName**.

- [msdyn_resourceassignment_SyncErrors](#BKMK_msdyn_resourceassignment_SyncErrors)
- [msdyn_resourceassignment_AsyncOperations](#BKMK_msdyn_resourceassignment_AsyncOperations)
- [msdyn_resourceassignment_MailboxTrackingFolders](#BKMK_msdyn_resourceassignment_MailboxTrackingFolders)
- [msdyn_resourceassignment_UserEntityInstanceDatas](#BKMK_msdyn_resourceassignment_UserEntityInstanceDatas)
- [msdyn_resourceassignment_ProcessSession](#BKMK_msdyn_resourceassignment_ProcessSession)
- [msdyn_resourceassignment_BulkDeleteFailures](#BKMK_msdyn_resourceassignment_BulkDeleteFailures)
- [msdyn_resourceassignment_PrincipalObjectAttributeAccesses](#BKMK_msdyn_resourceassignment_PrincipalObjectAttributeAccesses)
- [msdyn_msdyn_resourceassignment_msdyn_resourceassignmentdetail_resourceassignmentid](#BKMK_msdyn_msdyn_resourceassignment_msdyn_resourceassignmentdetail_resourceassignmentid)


### <a name="BKMK_msdyn_resourceassignment_SyncErrors"></a> msdyn_resourceassignment_SyncErrors

Same as syncerror entity [msdyn_resourceassignment_SyncErrors](syncerror.md#BKMK_msdyn_resourceassignment_SyncErrors) Many-To-One relationship.

**ReferencingEntity**: syncerror<br />
**ReferencingAttribute**: regardingobjectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_resourceassignment_SyncErrors<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: Cascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: Cascade
- **Share**: Cascade
- **Unshare**: Cascade


### <a name="BKMK_msdyn_resourceassignment_AsyncOperations"></a> msdyn_resourceassignment_AsyncOperations

Same as asyncoperation entity [msdyn_resourceassignment_AsyncOperations](asyncoperation.md#BKMK_msdyn_resourceassignment_AsyncOperations) Many-To-One relationship.

**ReferencingEntity**: asyncoperation<br />
**ReferencingAttribute**: regardingobjectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_resourceassignment_AsyncOperations<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: NoCascade
- **Delete**: NoCascade
- **Merge**: NoCascade
- **Reparent**: NoCascade
- **Share**: NoCascade
- **Unshare**: NoCascade


### <a name="BKMK_msdyn_resourceassignment_MailboxTrackingFolders"></a> msdyn_resourceassignment_MailboxTrackingFolders

Same as mailboxtrackingfolder entity [msdyn_resourceassignment_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_msdyn_resourceassignment_MailboxTrackingFolders) Many-To-One relationship.

**ReferencingEntity**: mailboxtrackingfolder<br />
**ReferencingAttribute**: regardingobjectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_resourceassignment_MailboxTrackingFolders<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: Cascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: Cascade
- **Share**: Cascade
- **Unshare**: Cascade


### <a name="BKMK_msdyn_resourceassignment_UserEntityInstanceDatas"></a> msdyn_resourceassignment_UserEntityInstanceDatas

Same as userentityinstancedata entity [msdyn_resourceassignment_UserEntityInstanceDatas](userentityinstancedata.md#BKMK_msdyn_resourceassignment_UserEntityInstanceDatas) Many-To-One relationship.

**ReferencingEntity**: userentityinstancedata<br />
**ReferencingAttribute**: objectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_resourceassignment_UserEntityInstanceDatas<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: NoCascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: NoCascade
- **Share**: NoCascade
- **Unshare**: NoCascade


### <a name="BKMK_msdyn_resourceassignment_ProcessSession"></a> msdyn_resourceassignment_ProcessSession

Same as processsession entity [msdyn_resourceassignment_ProcessSession](processsession.md#BKMK_msdyn_resourceassignment_ProcessSession) Many-To-One relationship.

**ReferencingEntity**: processsession<br />
**ReferencingAttribute**: regardingobjectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_resourceassignment_ProcessSession<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: NoCascade
- **Delete**: NoCascade
- **Merge**: NoCascade
- **Reparent**: NoCascade
- **Share**: NoCascade
- **Unshare**: NoCascade


### <a name="BKMK_msdyn_resourceassignment_BulkDeleteFailures"></a> msdyn_resourceassignment_BulkDeleteFailures

Same as bulkdeletefailure entity [msdyn_resourceassignment_BulkDeleteFailures](bulkdeletefailure.md#BKMK_msdyn_resourceassignment_BulkDeleteFailures) Many-To-One relationship.

**ReferencingEntity**: bulkdeletefailure<br />
**ReferencingAttribute**: regardingobjectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_resourceassignment_BulkDeleteFailures<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: NoCascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: NoCascade
- **Share**: NoCascade
- **Unshare**: NoCascade


### <a name="BKMK_msdyn_resourceassignment_PrincipalObjectAttributeAccesses"></a> msdyn_resourceassignment_PrincipalObjectAttributeAccesses

Same as principalobjectattributeaccess entity [msdyn_resourceassignment_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_msdyn_resourceassignment_PrincipalObjectAttributeAccesses) Many-To-One relationship.

**ReferencingEntity**: principalobjectattributeaccess<br />
**ReferencingAttribute**: objectid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_resourceassignment_PrincipalObjectAttributeAccesses<br />
**AssociatedMenuConfiguration**:

- **Behavior**: DoNotDisplay
- **Group**: Details
- **Label**: 
- **Order**: 

**CascadeConfiguration**:

- **Assign**: NoCascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: NoCascade
- **Share**: NoCascade
- **Unshare**: NoCascade


### <a name="BKMK_msdyn_msdyn_resourceassignment_msdyn_resourceassignmentdetail_resourceassignmentid"></a> msdyn_msdyn_resourceassignment_msdyn_resourceassignmentdetail_resourceassignmentid

Same as msdyn_resourceassignmentdetail entity [msdyn_msdyn_resourceassignment_msdyn_resourceassignmentdetail_resourceassignmentid](msdyn_resourceassignmentdetail.md#BKMK_msdyn_msdyn_resourceassignment_msdyn_resourceassignmentdetail_resourceassignmentid) Many-To-One relationship.

**ReferencingEntity**: msdyn_resourceassignmentdetail<br />
**ReferencingAttribute**: msdyn_resourceassignmentid<br />
**IsHierarchical**: False<br />
**IsCustomizable**: True<br />
**ReferencedEntityNavigationPropertyName**: msdyn_msdyn_resourceassignment_msdyn_resourceassignmentdetail_resourceassignmentid<br />
**AssociatedMenuConfiguration**:

- **Behavior**: UseCollectionName
- **Group**: Details
- **Label**: 
- **Order**: 10000

**CascadeConfiguration**:

- **Assign**: Cascade
- **Delete**: Cascade
- **Merge**: NoCascade
- **Reparent**: Cascade
- **Share**: Cascade
- **Unshare**: Cascade

<a name="manytoone"></a>

## Many-To-One Relationships

Each Many-To-One relationship is defined by a corresponding One-To-Many relationship with the related entity. Listed by **SchemaName**.

- [lk_msdyn_resourceassignment_createdby](#BKMK_lk_msdyn_resourceassignment_createdby)
- [lk_msdyn_resourceassignment_createdonbehalfby](#BKMK_lk_msdyn_resourceassignment_createdonbehalfby)
- [lk_msdyn_resourceassignment_modifiedby](#BKMK_lk_msdyn_resourceassignment_modifiedby)
- [lk_msdyn_resourceassignment_modifiedonbehalfby](#BKMK_lk_msdyn_resourceassignment_modifiedonbehalfby)
- [user_msdyn_resourceassignment](#BKMK_user_msdyn_resourceassignment)
- [team_msdyn_resourceassignment](#BKMK_team_msdyn_resourceassignment)
- [business_unit_msdyn_resourceassignment](#BKMK_business_unit_msdyn_resourceassignment)
- [msdyn_bookableresource_msdyn_resourceassignment_bookableresourceid](#BKMK_msdyn_bookableresource_msdyn_resourceassignment_bookableresourceid)
- [msdyn_bookingstatus_msdyn_resourceassignment_bookingstatusid](#BKMK_msdyn_bookingstatus_msdyn_resourceassignment_bookingstatusid)
- [msdyn_msdyn_project_msdyn_resourceassignment_projectid](#BKMK_msdyn_msdyn_project_msdyn_resourceassignment_projectid)
- [msdyn_msdyn_projecttask_msdyn_resourceassignment_taskid](#BKMK_msdyn_msdyn_projecttask_msdyn_resourceassignment_taskid)
- [msdyn_msdyn_projectteam_msdyn_resourceassignment_projectteamid](#BKMK_msdyn_msdyn_projectteam_msdyn_resourceassignment_projectteamid)


### <a name="BKMK_lk_msdyn_resourceassignment_createdby"></a> lk_msdyn_resourceassignment_createdby

See systemuser Entity [lk_msdyn_resourceassignment_createdby](systemuser.md#BKMK_lk_msdyn_resourceassignment_createdby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_resourceassignment_createdonbehalfby"></a> lk_msdyn_resourceassignment_createdonbehalfby

See systemuser Entity [lk_msdyn_resourceassignment_createdonbehalfby](systemuser.md#BKMK_lk_msdyn_resourceassignment_createdonbehalfby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_resourceassignment_modifiedby"></a> lk_msdyn_resourceassignment_modifiedby

See systemuser Entity [lk_msdyn_resourceassignment_modifiedby](systemuser.md#BKMK_lk_msdyn_resourceassignment_modifiedby) One-To-Many relationship.

### <a name="BKMK_lk_msdyn_resourceassignment_modifiedonbehalfby"></a> lk_msdyn_resourceassignment_modifiedonbehalfby

See systemuser Entity [lk_msdyn_resourceassignment_modifiedonbehalfby](systemuser.md#BKMK_lk_msdyn_resourceassignment_modifiedonbehalfby) One-To-Many relationship.

### <a name="BKMK_user_msdyn_resourceassignment"></a> user_msdyn_resourceassignment

See systemuser Entity [user_msdyn_resourceassignment](systemuser.md#BKMK_user_msdyn_resourceassignment) One-To-Many relationship.

### <a name="BKMK_team_msdyn_resourceassignment"></a> team_msdyn_resourceassignment

See team Entity [team_msdyn_resourceassignment](team.md#BKMK_team_msdyn_resourceassignment) One-To-Many relationship.

### <a name="BKMK_business_unit_msdyn_resourceassignment"></a> business_unit_msdyn_resourceassignment

See businessunit Entity [business_unit_msdyn_resourceassignment](businessunit.md#BKMK_business_unit_msdyn_resourceassignment) One-To-Many relationship.

### <a name="BKMK_msdyn_bookableresource_msdyn_resourceassignment_bookableresourceid"></a> msdyn_bookableresource_msdyn_resourceassignment_bookableresourceid

See bookableresource Entity [msdyn_bookableresource_msdyn_resourceassignment_bookableresourceid](bookableresource.md#BKMK_msdyn_bookableresource_msdyn_resourceassignment_bookableresourceid) One-To-Many relationship.

### <a name="BKMK_msdyn_bookingstatus_msdyn_resourceassignment_bookingstatusid"></a> msdyn_bookingstatus_msdyn_resourceassignment_bookingstatusid

See bookingstatus Entity [msdyn_bookingstatus_msdyn_resourceassignment_bookingstatusid](bookingstatus.md#BKMK_msdyn_bookingstatus_msdyn_resourceassignment_bookingstatusid) One-To-Many relationship.

### <a name="BKMK_msdyn_msdyn_project_msdyn_resourceassignment_projectid"></a> msdyn_msdyn_project_msdyn_resourceassignment_projectid

See msdyn_project Entity [msdyn_msdyn_project_msdyn_resourceassignment_projectid](msdyn_project.md#BKMK_msdyn_msdyn_project_msdyn_resourceassignment_projectid) One-To-Many relationship.

### <a name="BKMK_msdyn_msdyn_projecttask_msdyn_resourceassignment_taskid"></a> msdyn_msdyn_projecttask_msdyn_resourceassignment_taskid

See msdyn_projecttask Entity [msdyn_msdyn_projecttask_msdyn_resourceassignment_taskid](msdyn_projecttask.md#BKMK_msdyn_msdyn_projecttask_msdyn_resourceassignment_taskid) One-To-Many relationship.

### <a name="BKMK_msdyn_msdyn_projectteam_msdyn_resourceassignment_projectteamid"></a> msdyn_msdyn_projectteam_msdyn_resourceassignment_projectteamid

See msdyn_projectteam Entity [msdyn_msdyn_projectteam_msdyn_resourceassignment_projectteamid](msdyn_projectteam.md#BKMK_msdyn_msdyn_projectteam_msdyn_resourceassignment_projectteamid) One-To-Many relationship.

## See also

[About the Entity Reference](../about-entity-reference.md)<br />
[Programming reference for Dynamics 365 Customer Engagement](../programming-reference.md)<br />
[Web API Reference](/dynamics365/customer-engagement/web-api/about)<br />
<xref href="Microsoft.Dynamics.CRM.msdyn_resourceassignment?text=msdyn_resourceassignment EntityType" />