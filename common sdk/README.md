# NICE CXone Common SDK

*  [NPM package](https://www.npmjs.com/package/@nice-ccf/common-sdk)
*  [Sample Web App](https://github.com/nice-cxone/webapp-acd-cxagent-sdk-consumer)

## Requirements
*  TypeScript 4.9
*  Runtime: ES2022 (`WebSocket`, `Intl`, `Promise`, `EventTarget`, `CustomEvent`, `JSON`, `Date`, etc.)
*  Custom application bundler (webpack, create-react-app, etc.)

This library provides a comprehensive set of functionalities for building CXone applications. It offers various utilities, models, and helper functions to streamline common development tasks across different CXone applications.

## Features

* **Agent Management:** Models and functionalities for managing agents, including their state, sessions, events.
* **Authentication:** Models for handling authentication tokens and user information.
* **Communication:** Models and functionalities for various communication channels like voice, digital, and chat.
* **Customer Interaction:** Models for handling customer data, interaction history, and contact details.
* **Directories:** Models for managing directories and retrieving directory entries.
* **Message Bus:** Mechanisms for inter-component communication within the application.
* **Retry Logic:** Configuration options for retrying failed operations.
* **Search and Filtering:** Utilities for generating query URLs for searching across various entities (messages, customers, threads).
* **Time and Date:** Functions for parsing durations, converting milliseconds to time strings, and potentially formatting dates according to locale.
* **Data Parsing and Manipulation:** Utilities for parsing strings to booleans or integers, and calculating percentages.
* **Enums:** Enumerations for various concepts used throughout the library.
* **Utility Functions:** Helper functions for common tasks like data manipulation, formatting, and potentially logging.

## Benefits

* **Improved Developer Productivity:** The library provides pre-built components and functions, reducing the need for repetitive development work.
* **Code Maintainability and Consistency:** Consistent coding practices and modular design promote easier code maintenance and understanding.
* **Streamlined CXone Application Development:** The library offers functionalities specific to CXone applications, accelerating development lifecycles.

## Installation

```
npm install @nice-ccf/common-sdk
```

## Import necessary modules

```
import {
  AgentCurrentState,
  AgentDetails,
  AgentQueues,
  AgentQueuesDetail,
  AgentSkill,
  AgentState,
  AgentStateEvent,
  AgentSessionResponse,
  CallContactEvent,
  CoBrowseEvent,
  CXoneApiPerformanceMetrics,
  CXoneAudioVisualNotificationSettings,
  CXoneClientData,
  CXoneContactScreenpop,
  CXoneDispositionDetails,
  CXoneEvent,
  CXoneLeaderElector,
  CXonePageOpen,
  CXonePopUrl,
  CXoneRunApp,
  CXoneSdkError,
  CXoneSdkErrorType,
  CXoneSoftphoneNotificationSettings,
  CXoneTypingMessageContent,
  DirectoryEntities,
  EndSessionRequest,
  HttpResponse,
  IndicatorActionType,
  MediaType,
  MCHSetting,
  MessageBox,
  MessageType,
  PermissionKeys,
  PermissionValues,
  Queue,
  RunAppActionType,
  StartSessionRequest,
  TagsResponse,
  UnavailableCode,
  UpdateNetworkTimeoutEvent,
  VoiceMailContactEvent,
  VoiceMailPlayBackEvent,
  WorkItemContactEvent,
  WorkItemContactStatus,
} from '@nice-ccf/common-sdk';
```

## Usage

The library provides a modular structure. Import the specific functionalities you need from the relevant sub-modules within the src folder. Refer to the API documentation for detailed usage instructions for each function or model.

## License

This library is licensed under the (mention license here).

## Support

For any issues or questions, please refer to the (mention support channel/link here).

## Keywords

none