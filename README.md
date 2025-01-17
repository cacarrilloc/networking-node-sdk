[![Build Status](https://travis-ci.com/IBM/networking-node-sdk.svg?branch=master)](https://travis-ci.com/IBM/networking-node-sdk)
[![Release](https://img.shields.io/github/v/release/IBM/networking-node-sdk)](https://github.com/IBM/networking-node-sdk/releases/latest)
[![npm](https://img.shields.io/npm/v/ibm-networking-services)](https://www.npmjs.com/package/ibm-networking-services)
![npm](https://img.shields.io/npm/dm/ibm-networking-services)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

# IBM Cloud Networking Node.js SDK
Node.js client library to interact with various [IBM Cloud Networking Service APIs](https://cloud.ibm.com/docs?tab=api-docs&category=network).

Disclaimer: this SDK is being released initially as a **pre-release** version.
Changes might occur which impact applications that use this SDK.

## Table of Contents

<!--
  The TOC below is generated using the `markdown-toc` node package.

      https://github.com/jonschlinkert/markdown-toc

  You should regenerate the TOC after making changes to this file.

      npx markdown-toc -i README.md
  -->

<!-- toc -->

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Using the SDK](#using-the-sdk)
- [Questions](#questions)
- [Issues](#issues)
- [Open source @ IBM](#open-source--ibm)
- [Contributing](#contributing)
- [License](#license)

<!-- tocstop -->

<!-- --------------------------------------------------------------- -->
## Overview

The IBM Cloud Networking Service Node.js SDK allows developers to programmatically interact with the following
IBM Cloud services:

Service Name | Import Path
--- | ---
[Cloud Internet Service](https://cloud.ibm.com/apidocs/cis?code=node) | ibm-networking-services/cis/{service-name}/v1
[Direct Link](https://cloud.ibm.com/apidocs/direct_link?code=node) | ibm-networking-services/direct-link/v1
[Direct Link Provider](https://cloud.ibm.com/apidocs/direct_link_provider_api?code=node) | ibm-networking-services/direct-link-provider/v2
[DNS Service](https://cloud.ibm.com/apidocs/dns-svcs) | ibm-networking-services/dns-svcs/v1
[Transit Gateway](https://cloud.ibm.com/apidocs/transit-gateway?code=node) | ibm-networking-services/transit-gateway-apis/v1

## Prerequisites
* You need an [IBM Cloud][ibm-cloud-onboarding] account.
* **Node.js >=10**: This SDK is tested with Node.js versions 10 and up. It may work on previous versions but this is not officially supported.

[ibm-cloud-onboarding]: http://cloud.ibm.com/registration

## Installation

```sh
npm install ibm-networking-services
```

## Using the SDK
For general SDK usage information, please see
[this link](https://github.com/IBM/ibm-cloud-sdk-common/blob/master/README.md)

## Questions

If you are having difficulties using this SDK or have a question about the IBM Cloud services,
please ask a question at
[Stack Overflow](http://stackoverflow.com/questions/ask?tags=ibm-cloud).

## Issues
If you encounter an issue with the SDK, you are welcome to submit
a [bug report](https://github.com/IBM/networking-node-sdk/issues). 
Before that, please search for similar issues. It's possible someone has
already encountered this issue.

## Open source @ IBM
Find more open source projects on the [IBM Github Page](http://ibm.github.io/)

## Contributing
See [CONTRIBUTING](CONTRIBUTING.md).

## License

This project is released under the Apache 2.0 license.
The license's full text can be found in
[LICENSE](LICENSE).
