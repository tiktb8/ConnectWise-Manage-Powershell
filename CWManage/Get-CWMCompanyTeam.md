# Get-CWMCompanyTeam
## SYNOPSIS
This function will list of teams of a company based on conditions.
## SYNTAX
```powershell
Get-CWMCompanyTeam [[-CompanyID] <Int32>] [[-Condition] <String>] [[-orderBy] <Object>] [[-childconditions] <String>] [[-customfieldconditions] <String>] [[-page] <Int32>] [[-pageSize] <Int32>] [-all] [<CommonParameters>]
```
## PARAMETERS
### -CompanyID &lt;Int32&gt;

```
Required                    false
Position                    1
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -Condition &lt;String&gt;
The id of the company you want to get the teams of.
```
Required                    false
Position                    2
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -orderBy &lt;Object&gt;
Choose which field to sort the results by
```
Required                    false
Position                    3
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -childconditions &lt;String&gt;
Allows searching arrays on endpoints that list childConditions under parameters
```
Required                    false
Position                    4
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -customfieldconditions &lt;String&gt;
Allows searching custom fields when customFieldConditions is listed in the parameters
```
Required                    false
Position                    5
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -page &lt;Int32&gt;
Used in pagination to cycle through results
```
Required                    false
Position                    6
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -pageSize &lt;Int32&gt;
Number of results returned per page (Defaults to 25)
```
Required                    false
Position                    7
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -all &lt;SwitchParameter&gt;
Return all results
```
Required                    false
Position                    named
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
## EXAMPLES
### EXAMPLE 1
```powershell
PS C:\>Get-CWMCompanyTeam -CompanyID 1 -all

Will return all team members for company 1
```

## NOTES
Author: Chris Taylor

Date: 10/25/2018 
## LINKS
http://labtechconsulting.com

https://developer.connectwise.com/products/manage/rest?a=Company&e=CompanyTeams&o=GET
