# 2025-research-plan
**EPIC** – Research Goals and Improvements.

## The AwesomeOS Project
- [ ] Packaging/Deployment/Execution of CLI Software.
- [ ] Packaging/Deployment/Execution of Autonomous Web Agents on Google Chrome / Chromium / ChromeOS / FuchsiaOS / AwesomeOS.
- [ ] Packaging/Deployment/Execution of Autonomous Linux Deployments with (GNU + GNOME).
- [ ] Packaging/Deployment/Execution of Autonomous Windows Deployments using Windows Subsystem for Linux (WSL) (https://github.com/microsoft/WindowsAgentArena).

## Data Storage and Processing
- [ ] Quaternion DB: More generic deployment strategies and use case implementation at scale.
- [ ] BTRFS tooling and improved Windows interoperability. Also, research the smallest common denominators between ReFS and BTRFS to align them if possible.

## IDE
- [ ] Implement the first VSCode extensions of their kind and document the new plugin system based on ESM behavior. (https://github.com/microsoft/vscode/issues/226260)
- [ ] Consolidate research on the Unlicense Code Editor Project.

## Content Production
- [ ] Scale content production, not only in quantity but also in quality and reduce the time needed to achieve output.

## Improve Autonomous Development
Consolidate the research on **just-js**, **B8G Compiler**, **AwesomeOS**, and **v8 bundling**. Train the AwesomeOS Developer MMA (Multi-Modal Agent) system to accomplish tasks with less input and fewer iterations. Teach it more about common denominators and findings regarding scalable software development strategies. Prepare for direct assembler compilation and execution inside v8.

## Why is v8 such a core part of the research?
V8 is a highly extensible compiler that allows easy execution of isolated workloads while having good interoperability with text syntax via the ECMAScript language. Tagged template string literals allow us to express code written in different languages, as demonstrated by the B8G Compiler and Stealify Lang.

