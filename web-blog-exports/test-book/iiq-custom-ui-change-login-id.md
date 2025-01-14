---
title: "IIQ Custom UI Change Login ID"
description: ""
date: "2022-02-24T13:00:27.000000Z"
lastmod: "2022-04-04T14:13:03.000000Z"
bookstack_id: 32
params:
  author: "Andre Grosse Festert"
tags:

# no cover found.
---

# IIQ Custom UI Change Login ID

To change Login ID with Custom UI for a Identity use the Button "Change Login ID" (only available for Identities)  
<span style="color: #ff0000;">\*\*\* ATTENTION \*\*\* Please check whether the Login ID to be assigned is not already in use</span>

[![image-1645707974974.png](../images/image-1645707974974.png)](../images/image-1645707974974.png)

Before we change the Login ID we need to check the following  
In this case the Login ID llaus schould be changed to lkonrad

##### Login ID check via Identity Informations

[![image-1645709039230.png](../images/image-1645709039230.png)](../images/image-1645709039230.png)

If Login ID not changed to the new one via Staging check in Debug &gt; Propagation &gt; Staging

##### Check if Login ID already changed by Staging or prepared

[![image-1645708495778.png](../images/image-1645708495778.png)](../images/image-1645708495778.png)

[![image-1645708819324.png](../images/image-1645708819324.png)](../images/image-1645708819324.png)

In this case the Login ID was already changed by Staging and must not be changed via Standard UI in .xml and we can start to change the Login ID to fix the CLDAP Propagation.

##### Check CLDAP Propagation

[![image-1645710036710.png](../images/image-1645710036710.png)](../images/image-1645710036710.png)

The Login ID was not changed for the Identity so we can start.  
To change Login ID with Custom UI for a Identity use the Button "Change Login ID" (only available for Identities)

[![image-1645707974974.png](../images/image-1645707974974.png)](../images/image-1645707974974.png)

Old Login ID  
[![image-1645710285108.png](../images/image-1645710285108.png)](../images/image-1645710285108.png)

New Login ID  
[![image-1645710373218.png](../images/image-1645710373218.png)](../images/image-1645710373218.png)

Waiting ...

[![image-1645710607008.png](../images/image-1645710607008.png)](../images/image-1645710607008.png)

After successful change we check the CLDAP Propagation again.

[![image-1645710816409.png](../images/image-1645710816409.png)](../images/image-1645710816409.png)

Login ID was successfully changes from llaus to lkonrad

##### Change Exchange Native ID via debug after Login ID change

Please change also the Exchange Native ID after successfully Login ID change

[![image-1649081299426.png](../images/image-1649081299426.png)](../images/image-1649081299426.png)

Change Exchange Native ID via debug mode with Standard UI in xml

[![image-1649081413581.png](../images/image-1649081413581.png)](../images/image-1649081413581.png)

[![image-1649081438895.png](../images/image-1649081438895.png)](../images/image-1649081438895.png)

Save xml and check again with UI

[![image-1649081561896.png](../images/image-1649081561896.png)](../images/image-1649081561896.png)
