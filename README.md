# SAP PowerDesigner Extension to Generate HDB Artifacts

## Description
This extension shows how to develop HDBTable and HDBMigrationTable scripts that are generated out of SAP PowerDesigner.

## Requirements
You need [SAP PowerDesigner](https://www.sap.com/products/powerdesigner-data-modeling-tools.html) (DataArchitect edition, EnterpriseArchitect edition, or trial version).

## Download and Installation
This git repository contains 
 - a HDBTABLE.xem that has to be added to your own PD extensions

## Known Issues
 - only for tables and only with a standard set of functions
 - does not contain syntax support for system version or partitioning
 - does not support syntay support for views or any other HANA artifacts
 - You have to manual disable "Migration" in the compare dialog
 - You have to manual add the delta to the table migrations
 - This function is only for PowerDesigner and do not work in the portal

## Documentation
[Find the instructions here](https://github.com/SAP-samples/hana-cloud-workshop-powerdesigner-extension/blob/main/Instructions/Readme.md).

## How to obtain support

[Create an issue](https://github.com/SAP-samples/hana-cloud-workshop-powerdesigner-extension/issues) in this repository if you find a bug or have questions about the content.
 
For additional support, [ask a question in SAP Community](https://answers.sap.com/questions/ask.html).

## License
Copyright (c) 2021 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/hana-cloud-workshop-powerdesigner-extension)](https://api.reuse.software/info/github.com/SAP-samples/hana-cloud-workshop-powerdesigner-extension)