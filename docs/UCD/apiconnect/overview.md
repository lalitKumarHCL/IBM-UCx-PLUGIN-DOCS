
# IBM API Connect - Overview

The API Connect plug-in includes steps that publish API definitions, products, and Loopback apps in IBM API Connect. The plug-in communicates with API Connect using the `apiconnect` contained in the apic command line toolkit.

This plug-in includes the following steps:

* [Login](#login)
* [Logout](#logout)
* [Publish API Product Definitions](#publish_api_product_definitions)
* [Publish an Application (API Connect v5.x)](#publish_an_application_(api_connect_v5.x))
* [Push API Product Definitions to Drafts (API Connect v5.x)](#push_api_product_definitions_to_drafts_(api_connect_v5.x))
* [Replace Product in Catalog](#replace_product_in_catalog)
* [Set Configuration Variable](#set_configuration_variable)
* [Supersede Product in Catalog](#supersede_product_in_catalog)


### Step palette

To access this plug-in in the palette, click **IBM API Management** > **IBM API Connect**.

### Compatibility

This plug-in is supported to run on all operating systems that are supported by both the IBM UrbanCode Deploy agent (except for z/OS) and the apic toolkit. This plug-in supports apic v2.0.18 and higher. Authentication issues exist within the apic toolkit. See [Troubleshooting](#troubleshooting) for a workaround.

This plug-in requires version 6.0.1 or later of IBM UrbanCode Deploy.

This plug-in is compatible with agents running on operating systems that are supported by both IBM UrbanCode Deploy and the apiconnect (apic) command line toolkit. This plug-in does not support agents running on z/OS.

### Installation

No special steps are required for installation. See [Installing plug-ins in UrbanCode Deploy](https://community.ibm.com/community/user/wasdevops/blogs/laurel-dickson-bull1/2022/06/13/install-plugins "Installing plug-ins in UrbanCode Deploy").

The apic toolkit must be downloaded and installed separately. Directions can be found [Installing the toolkit](https://www.ibm.com/support/knowledgecenter/SSMNED_5.0.0/com.ibm.apic.toolkit.doc/tapim_cli_install.html) topic in the product documentation.

### History

#### Version 6

* Allow space to be specified on the Publish API Product Definitions (products:publish) and Replace Product in Catalog (products:replace) steps.

#### Version 5

* Added Replace Product in a Catalog step.
* Updated Set Configuration Variable step to not add extra spaces.

#### Version 4

* Support property file encryption.
#### Version 3

* Version 3 brings support to apic v2.0.18 and the following features:
+ Remove the type property from the Login step.
+ Error handling has been updated.

#### Version 2

* Version 2 brings updates to step names, property names, and templates for better comprehension.

#### Version 1

* Initial beta release containing steps to deploy API Definitions, Products, and Loopback apps to IBM API Connect.

|Back to ...||Latest Version|IBM API Connect ||||||
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|[All Plugins](../../index.md)|[Deploy Plugins](../README.md)|[7.1022553](https://raw.githubusercontent.com/UrbanCode/IBM-UCD-PLUGINS/main/files/apiconnect/apiconnect-7.1022553.zip)|[Readme](README.md)|[Usage](usage.md)|[Tutorials](tutorials.md)|[Steps](steps.md)|[Troubleshooting](troubleshooting.md)|[Downloads](downloads.md)|
