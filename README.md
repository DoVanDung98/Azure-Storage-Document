# Azure Storage Document 
```
    Azure Storage offers a massively scalabel object store for data object,    
    a file system service for the cloud, a messaging store for  
    the cloud, and a NoSQL store
```

```
    Storage Account:
        Blob  
        File
        Queue
        Table
```  

```
    Blob Storage:
        A massively scalable object store for text and binay data.  
        Ideal for:
            - Serving images or document directly to a brower
            - Storing files for distributed access
            - Streaming video and audio
            - Storing data for backup and resotre, disaster recovery, and archiving
            - Storing data for analysis by an on-permises or Azure-hosted service
    
    Blob Storage Access Tier 
        Azure  Storage providers different options for accessing block
        blob data based on usage patterns. 
            - Hot: opimized for frequent access of objects
            - Cool: optimized for storing large amounts of data that is 
            infrequently accessed and stored for at least 30 days
            - Archive: optimized for data that can tolerate several hours
            of retrieval latency and will remain in the Archive tier for 
            at least 180 days
    
    File Storage: 
        Managed file shares for cloud or on-permises deployments.  
    
    Storage Queue:
        A messaging store for reliable messaging between application components.  
    
    Table Storage:
        A NoSQL store for schemaless storage of  structured data.
```
```
    Storage Performance Tier
        General-purpose storage accounts may be configured for either 
        of the following performace tiers.
        - A standard performance tier for storing blob, files, tables,
        queues, and Azure virtual machine disks.
        - A premium performance tier for storing unmanaged virtual 
        machine disks only.
```
```
    Data Redundancy
        Azure Storage replicate mutilple copies of your data.
        Replication options for a storage account include:
            - Locally-redundant storage(LRS)
            - Zone-redundant storage(ZRS)
            - Geo-redundant storage(GRS)
            - Read-access geo-redundant storage(RA_GRS)
```
```
    Locally-redundant storage(LRS):
        A simple, low-cost replication strategy.
        Data is replicated within a single storage scale unit.
    Zone-redundant storage(ZRS):
        Replication for high availability and durability.
        Data is replicated synchronously across three availability zones.
    Geo-redundant storage(GRS):
        Cross-regional replicationto protect against region-wide 
        unvailability
```
