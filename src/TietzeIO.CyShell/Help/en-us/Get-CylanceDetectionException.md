---
external help file: TietzeIO.CyShell.dll-Help.xml
Module Name: TietzeIO.CyShell
online version:
schema: 2.0.0
---

# Get-CylanceDetectionException

## SYNOPSIS
Retrieves details for a detection exception

## SYNTAX

```
Get-CylanceDetectionException -DetectionException <CyDetectionExceptionMetaData> [-Api <ApiConnectionHandle>]
 [<CommonParameters>]
```

## DESCRIPTION
Retrieves details for a detection exception

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -Api
An API session handle (global session handle will be used if none exists in the current session).

```yaml
Type: ApiConnectionHandle
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DetectionException
{{ Fill DetectionException Description }}

```yaml
Type: CyDetectionExceptionMetaData
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### TietzeIO.CyAPI.Entities.Optics.CyDetectionExceptionMetaData

## OUTPUTS

### TietzeIO.CyAPI.Entities.Optics.CyDetectionException

## NOTES

## RELATED LINKS
