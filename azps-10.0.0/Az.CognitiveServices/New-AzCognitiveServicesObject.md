---
external help file: Microsoft.Azure.PowerShell.Cmdlets.CognitiveServices.dll-Help.xml
Module Name: Az.CognitiveServices
online version: https://learn.microsoft.com/powershell/module/az.cognitiveservices/new-azcognitiveservicesobject
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/CognitiveServices/CognitiveServices/help/New-AzCognitiveServicesObject.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/main/src/CognitiveServices/CognitiveServices/help/New-AzCognitiveServicesObject.md
---

# New-AzCognitiveServicesObject

## SYNOPSIS
Create a Cognitive Services Object

## SYNTAX

```
New-AzCognitiveServicesObject [-Type] <CognitiveServicesObjectType> [-DefaultProfile <IAzureContextContainer>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create a Cognitive Services Object

## EXAMPLES

### Example 1
```powershell
New-AzCognitiveServicesObject -Type DeploymentProperties
```

Create a Cognitive Services DeploymentProperties Object

## PARAMETERS

### -DefaultProfile
The credentials, account, tenant, and subscription used for communication with Azure.

```yaml
Type: Microsoft.Azure.Commands.Common.Authentication.Abstractions.Core.IAzureContextContainer
Parameter Sets: (All)
Aliases: AzContext, AzureRmContext, AzureCredential

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Type
Cognitive Services Object Type.

```yaml
Type: Microsoft.Azure.Commands.Management.CognitiveServices.CognitiveServicesObjectType
Parameter Sets: (All)
Aliases:
Accepted values: DeploymentProperties, CommitmentPlanProperties, MultiRegionSettings, RegionSetting

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### Microsoft.Azure.Management.CognitiveServices.Models.DeploymentProperties

### Microsoft.Azure.Management.CognitiveServices.Models.CommitmentPlanProperties

## NOTES

## RELATED LINKS
