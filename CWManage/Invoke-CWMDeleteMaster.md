# Invoke-CWMDeleteMaster
## SYNOPSIS
This will be basis of all delete calls to the ConnectWise Manage API.
## SYNTAX
```powershell
Invoke-CWMDeleteMaster [[-Arguments] <Object>] [[-URI] <String>] [<CommonParameters>]
```
## DESCRIPTION
This will insure that all delete requests are handled correctly.
## PARAMETERS
### -Arguments &lt;Object&gt;
A hash table of parameters
```
Required                    false
Position                    1
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -URI &lt;String&gt;
The URI of the delete endpoint
```
Required                    false
Position                    2
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
## EXAMPLES
### EXAMPLE 1
```powershell
PS C:\>Invoke-CWMDeleteMaster -Arguments $Arguments -URI $URI
```

## NOTES
Author: Chris Taylor

Date: 10/10/2018 
