---
external help file: 
applicable: SharePoint Server 2013, SharePoint Server 2016
title: Add-SPDistributedCacheServiceInstance
schema: 2.0.0
---

# Add-SPDistributedCacheServiceInstance

## SYNOPSIS

{{Fill in the Synopsis}}



## SYNTAX

###  (Default)
```
Add-SPDistributedCacheServiceInstance [-AssignmentCollection <SPAssignmentCollection>] [<CommonParameters>]
```

### CacheSizeSet
```
Add-SPDistributedCacheServiceInstance [-AssignmentCollection <SPAssignmentCollection>] [-CacheSizeInMB <Int32>]
 [<CommonParameters>]
```

### LocalServerRoleSet
```
Add-SPDistributedCacheServiceInstance [-AssignmentCollection <SPAssignmentCollection>] [-Role <SPServerRole>]
 [<CommonParameters>]
```

## DESCRIPTION

{{Fill in the Description}}



## EXAMPLES

### Example 1 
```
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -AssignmentCollection

{{Fill AssignmentCollection Description}}



```yaml
Type: SPAssignmentCollection
Parameter Sets: (All)
Aliases: 
Applicable: SharePoint Server 2013, SharePoint Server 2016

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CacheSizeInMB
{{Fill CacheSizeInMB Description}}

```yaml
Type: Int32
Parameter Sets: CacheSizeSet
Aliases: 
Applicable: SharePoint Server 2016

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Role
{{Fill Role Description}}

```yaml
Type: SPServerRole
Parameter Sets: LocalServerRoleSet
Aliases: 
Accepted values: DistributedCache, SingleServerFarm, WebFrontEndWithDistributedCache
Applicable: SharePoint Server 2016

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.SharePoint.PowerShell.SPAssignmentCollection

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS

[Remove-SPDistributedCacheServiceInstance]()

