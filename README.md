# Sigrid Open Source Health greenhouse

This repository targets people using [Sigrid](https://www.softwareimprovementgroup.com/sigrid-core/).
Specifically, it targets people using **on-premise Sigrid**. 

Sigrid allows you to monitor the vulnerabilities, license, and freshness for your open source dependencies. 
On-premise Sigrid runs in air-gapped environments, meaning there is no outbound internet access. This leads
to a "catch 22" when you're using an open source library that is not yet available from Sigrid's knowledge base.

- Sigrid cannot report on the vulnerabilities/license/freshness for this library, since it's not in the knowledge base.
- But it cannot be added to the knowledge base, since you're in an air-gapped environment and there is no outbound
  internet access.
  
This repository offers a solution: Adding open source libraries to this project will also add them to Sigrid's
knowledge base, making them available to you when you update your on-premise Sigrid.

## How to make a request

Create a pull request on this project, and add your requested libraries. The version doesn't matter, although it's
probably best to use a version that is similar to what you're currently using. 

This project already contains several example files for popular open source libraries. but it's fine to add
additional files if your request requires it.  You can use any
[open source ecosystem](https://docs.sigrid-says.com/reference/technology-support.html#supported-open-source-ecosystems)
that is supported by Sigrid.

## License

Copyright Software Improvement Group

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    