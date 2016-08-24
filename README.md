# oracle-public-cloud-dse [Work In Progress]
Scripts for deploying DataStax Enterprise (DSE) to Oracle Public Cloud (OPC)

These don't work yet, sorry.

These scripts will use the Oracle Public Cloud (OPC) [CLI](https://docs.oracle.com/cloud-machine/latest/stcomputecs/ELUCL/GUID-A377A4D6-8A3E-43EF-B069-5C4EA50D7E6D.htm#ELACI113) to deploy a DataStax Enterprise cluster in an OPC environment:

 The [DataStax Enterprise Deployment Guide for Oracle Public Cloud](http://www.datastax.com) is a good place to learn how to use these assets to provision a DataStax Enterprise cluster in your Oracle Public Cloud environment.

Directory | Description
--- | ---
[extensions](./extensions) | Common scripts that are used by OPC instance's bootstrapping process. In OPC terminology, this process is referred as "Automating Instance Configuration Using opc-init".  You can learn more about this [here](http://docs.oracle.com/cloud/latest/stcomputecs/STCSG/GUID-C63680F1-1D97-4984-AB02-285B17278CC5.htm#STCSG-GUID-C63680F1-1D97-4984-AB02-285B17278CC5).
[root](https://github.com/DSPN/oracle-compute-cloud-dse/tree/master/) | Python and bash scripts to generate OPC CLI compliant json templates to stand up a DataStax Enterprise cluster in an OPC environment.

