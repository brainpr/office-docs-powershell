---
external help file:
online version: https://docs.microsoft.com/powershell/module/sharepoint-pnp/get-pnplistinformationrightsmanagement
applicable: SharePoint Server 2013, SharePoint Server 2016, SharePoint Server 2019, SharePoint Online
schema: 2.0.0
title: Get-PnPListInformationRightsManagement
---

# Get-PnPListInformationRightsManagement

## SYNOPSIS
Get the site closure status of the site which has a site policy applied

## SYNTAX 

```powershell
Get-PnPListInformationRightsManagement -List <ListPipeBind>
                                       [-Web <WebPipeBind>]
                                       [-Connection <PnPConnection>]
```

## EXAMPLES

### ------------------EXAMPLE 1------------------
```powershell
Get-PnPListInformationRightsManagement -List "Documents"
```

Returns Information Rights Management (IRM) settings for the list. See 'Get-Help Set-PnPListInformationRightsManagement -Detailed' for more information about the various values.

## PARAMETERS

### -List


```yaml
Type: ListPipeBind
Parameter Sets: (All)

Required: True
Position: Named
Accept pipeline input: False
```

### -Connection
Optional connection to be used by the cmdlet. Retrieve the value for this parameter by either specifying -ReturnConnection on Connect-PnPOnline or by executing Get-PnPConnection.

```yaml
Type: PnPConnection
Parameter Sets: (All)

Required: False
Position: Named
Accept pipeline input: False
```

### -Web
This parameter allows you to optionally apply the cmdlet action to a subweb within the current web. In most situations this parameter is not required and you can connect to the subweb using Connect-PnPOnline instead. Specify the GUID, server relative url (i.e. /sites/team1) or web instance of the web to apply the command to. Omit this parameter to use the current web.

```yaml
Type: WebPipeBind
Parameter Sets: (All)

Required: False
Position: Named
Accept pipeline input: False
```

## RELATED LINKS

[SharePoint Developer Patterns and Practices](https://aka.ms/sppnp)