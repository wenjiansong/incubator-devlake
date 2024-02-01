<!--
Licensed to the Apache Software Foundation (ASF) under one or more
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership.
The ASF licenses this file to You under the Apache License, Version 2.0
(the "License"); you may not use this file except in compliance with
the License.  You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->
<div align="center">
<br/>
<img src="resources/img/logo.svg" width="120px" alt="">
<br/>

# Apache DevLake(Incubating)

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat&logo=github&color=2370ff&labelColor=454545)](http://makeapullrequest.com)
[![Dockerhub pulls](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhub.docker.com%2Fv2%2Frepositories%2Fapache%2Fdevlake&query=%24.pull_count&label=Dockerhub%20pulls)](https://hub.docker.com/r/apache/devlake)
[![unit-test](https://github.com/apache/incubator-devlake/actions/workflows/test.yml/badge.svg)](https://github.com/apache/incubator-devlake/actions/workflows/test.yml)
[![Go Report Card](https://goreportcard.com/badge/github.com/apache/incubator-devlake)](https://goreportcard.com/report/github.com/apache/incubator-devlake)
[![Slack](https://img.shields.io/badge/slack-join_chat-success.svg?logo=slack)](https://join.slack.com/t/devlake-io/shared_invite/zt-18uayb6ut-cHOjiYcBwERQ8VVPZ9cQQw)
[![Twitter](https://badgen.net/badge/icon/twitter?icon=twitter&label)](https://twitter.com/ApacheDevLake)

</div>
<br>
<div align="left">

## 🤔 What is Apache DevLake?

[Apache DevLake](https://devlake.apache.org) is an open-source dev data platform that ingests, analyzes, and visualizes the fragmented data from DevOps tools to extract insights for engineering excellence, developer experience, and community growth.

Apache DevLake is designed for developer teams looking to make better sense of their development process and to bring a more data-driven approach to their own practices. You can ask Apache DevLake many questions regarding your development process. Just connect and query.

## 🎯 What can be accomplished with Apache DevLake?

1. Your Dev Data lives in many silos and tools. DevLake brings them all together to give you a complete view of your Software Development Life Cycle (SDLC).
2. From DORA to scrum retros, DevLake implements metrics effortlessly with prebuilt dashboards supporting common frameworks and goals.
3. DevLake fits teams of all shapes and sizes, and can be readily extended to support new data sources, metrics, and dashboards, with a flexible framework for data collection and transformation.

## 👉 Live Demo
[DORA Dashboard](https://grafana-lake.demo.devlake.io/grafana/d/qNo8_0M4z/dora?orgId=1)

[All Dashboards](https://devlake.apache.org/livedemo/EngineeringLeads/DORA)

## 💪 Supported Data Sources

[Here](https://devlake.apache.org/docs/Overview/SupportedDataSources) you can find all data sources supported by DevLake, their scopes, supported versions and more!


## 🚀 Getting Started

- [Install via Docker Compose](https://devlake.apache.org/docs/GettingStarted/DockerComposeSetup)
- [Install via Helm](https://devlake.apache.org/docs/GettingStarted/HelmSetup)
- [Install in Developer Mode](https://devlake.apache.org/docs/DeveloperManuals/DeveloperSetup)

## 🤓 How do I use DevLake?

### 1. Set up DevLake

You can set up Apache DevLake by following our step-by-step instructions for [Install via Docker Compose](https://devlake.apache.org/docs/GettingStarted/DockerComposeSetup) or [Install via Helm](https://devlake.apache.org/docs/GettingStarted/HelmSetup).
Please see detailed instructions [here](https://devlake.apache.org/docs/Overview/Introduction#how-do-i-use-devlake), and ask the community if you get stuck at any point.

### 2. Create a Blueprint

The DevLake Configuration UI will guide you through the process (a Blueprint) to define the data connections, data scope, transformation and sync frequency of the data you wish to collect.

### 3. Track the Blueprint's progress

You can track the progress of the Blueprint you have just set up.

### 4. View the pre-built dashboards

Once the first run of the Blueprint is completed, you can view the corresponding dashboards.

### 5. Customize the dashboards with SQL

If the pre-built dashboards are limited for your use cases, you can always customize or create your own metrics or dashboards with SQL.

## 😍 How to Contribute

Please read the [contribution guidelines](https://devlake.apache.org/community) before you make contribution. The following docs list the resources you might need to know after you decided to make contribution.

- [Create an Issue](https://devlake.apache.org/community/MakingContributions/fix-or-create-issues): Report a bug or feature request to Apache DevLake
- [Submit a PR](https://devlake.apache.org/community/MakingContributions/development-workflow): Start with [good first issues](https://github.com/apache/incubator-devlake/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) or [issues with no assignees](https://github.com/apache/incubator-devlake/issues?q=is%3Aissue+is%3Aopen+no%3Aassignee)
- [Join Mailing list](https://devlake.apache.org/community/subscribe): Initiate or participate in project discussions on the mailing list
- [Write a Blog](https://devlake.apache.org/community/MakingContributions/BlogSubmission): Write a blog to share your use cases about Apache DevLake
- [Develop a Plugin](./backend/DevelopmentSetup): [Add a plugin](https://github.com/apache/incubator-devlake/issues?q=is%3Aissue+is%3Aopen+label%3Aadd-a-plugin+) to integrate Apache DevLake with more data sources for the community

## 📄 Contributing to Documentation:

- Apache DevLake's documentation is hosted at [devlake.apache.org](https://devlake.apache.org/)
- **We have a separate GitHub repository for Apache DevLake's documentation:** [github.com/apache/incubator-devlake-website](https://github.com/apache/incubator-devlake-website)

## ⌚ Roadmap

- <a href="https://devlake.apache.org/docs/Overview/Roadmap" target="_blank">Roadmap</a>: Detailed roadmaps for DevLake.

## 💙 Community

- Slack: Message us on <a href="https://join.slack.com/t/devlake-io/shared_invite/zt-18uayb6ut-cHOjiYcBwERQ8VVPZ9cQQw" target="_blank">Slack</a>
- Wechat Community: [Check the barcode](resources/img/wechat_community_barcode.png)

## 📄 License<a id="license"></a>

This project is licensed under Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

</div>
## **Change logs**
