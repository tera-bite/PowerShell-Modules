# UserAccountUtilities.psm1
This module contains many useful cmdlets for administering AD User accounts.
Usage: Import-Module UserAccountUtilities.psm1

## Replace-AttributeInDirectory
  * A method to conditionally update the property of all AD accounts from the specified value to the new value
  
  * Examplpe: Replace-AttributeInDirectory -AttributeName Office -OldAttributeValue "China" -NewAttributeValue "London"