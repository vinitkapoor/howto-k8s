Purpose: Configure a Pod to use a PVC storage. Mount the storage as volume to the PoD. 

**Use Case Scenarios:**
1. Pod should be able mount the PVC as volume
2. Pod should be able to write to the volume
3. Pod should be able to read from the volume
4. If Pod is deleted, the data in the PV/PVC should be retained and not get deleted. 


**Design:**
StorageClass:

Pod

PV

PVC


