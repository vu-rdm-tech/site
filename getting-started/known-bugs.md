# Known bugs and workarounds
_Updated 2025-06-11_

### - Dataset can be archived and published with a missing ORCID field
- A user can add a creator or contributor, select ORCID as "Person identifier", but leave the "Identifier" field blank. The "required for Vault" bar will show the form is incomplete, but you can still submit it to the Vault. When you publish the dataset the person will be missing from the DataCite metadata.

### - Group manager cannot delete or change role of new user with an open SRAM invitation. This status is only updated 24 hours after the invitation has been accepted
- New users are also added with Read/Write rights, a new user intended as read-only will have temporary write access.

## Recently fixed

### - Datasets can be submitted without mandatory Creator Affiliation name
_Fixed 2025-06-04_
When leaving the [Creator] [Affiliation Name] field empty, the system will indicate clearly that the metadata form is not complete by marking the field with a red border and showing the green "Required for the vault" bar as incomplete. 
On clicking "submit" the system should show an error "Metadata is not valid, please open metadata form for more information", but it does not and the dataset is allowed to be further processed and can be secured in the Vault normally. 
If the dataset is later submitted and approved for publication the publication process fails and no resolvable DOI is generated.

Make sure Affiliation names are added for each Creator. Note that if the institute is not in the dropdown list you can just type the Name and leave the identifier field empty.
