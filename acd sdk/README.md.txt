# NICE CXone ACD SDK

*  [NPM package](https://www.npmjs.com/package/@nice-ccf/acd-sdk)
*  [Sample Web App](https://github.com/nice-cxone/webapp-acd-cxagent-sdk-consumer)

## Requirements
*  TypeScript 4.9
*  Runtime: ES2022 (`WebSocket`, `Intl`, `Promise`, `EventTarget`, CustomEvent`, `JSON`, `Date`, etc.)
*  Custom application bundler (webpack, create-react-app, etc.)


This README file provides an overview of the @nice-ccf/acd-sdk library, a Node.js library that empowers developers to interact with Automatic Call Distribution (ACD) functionalities within their applications built for the NICE CXone platform.

## Features (Likely)

* **ACD Engagement:** Start and end ACD sessions, manage agent state (available, unavailable, etc.).
* **Contact Management:** Interact with voicemails, work items, and potentially other contact-related functionalities (to be confirmed with documentation).
* **Skill Management:** Retrieve information about agent skills.
* **Team Unavailable Codes:** Fetch team unavailable codes.
* **Notifications:** Receive ACD notifications based on the dependency on @nice-ccf/agent-sdk.
* **Agent Details:** Retrieve agent details based on the presence of the agent-details service.

Uncertainties

The exact functionalities and their implementation details might differ based on the use of the peer dependencies.
The codebase (src/lib/acd) might reveal additional functionalities beyond what can be inferred from dependencies.

Installation

Bash
```
npm install @nice-ccf/acd-sdk
```

Usage

1. **Import necessary modules:**
```
import { /* functionalities from acd-sdk */ } from '@nice-ccf/acd-sdk';
```
2. **(Optional) Initialize the SDK (if required):**

```
// If the SDK requires initialization, follow instructions from the documentation
const acdClient = /* Initialize the ACD client object */;
```

3. **Leverage SDK functionalities:**

Refer to the official documentation (link to be provided, once found) for detailed usage examples on specific functionalities.
Explore the available classes and methods within the library (src/lib/acd) to interact with ACD features.
Documentation

For comprehensive API reference and usage examples, refer to the official documentation provided by NICE CXone (link to be retrieved).

## Compatibility

This SDK is likely compatible with specific ACD platform versions supported by its peer dependencies (e.g., @nice-ccf/agent-sdk, @nice-ccf/common-sdk). Refer to the official documentation (if available) for supported versions.

## License

Check the license file (LICENSE) for specific terms regarding the use of this SDK.

## Additional Notes

The SDK likely interacts with other NICE CXone products based on the peer dependencies (@nice-ccf/core-sdk, @nice-ccf/common-sdk).
Consider exploring the codebase (src/lib/acd) for a more comprehensive understanding of the functionalities offered.

## Keywords

none