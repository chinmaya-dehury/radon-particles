# Purpose: 
To get the data/objects from the AWS S3Bucket.

## Ansible Implementation:    
### Default implementation:  
Contains the Nifi processor to list the objects (ListS3) and fetch all the Objects based on the list using (FetchS3Object).
### Specific implementaion:
User need to provide the specific object name


@TODO: 
- Unable to set the use get_attrib in the interface definition. On doing so, winery is throwing an error.
- 


