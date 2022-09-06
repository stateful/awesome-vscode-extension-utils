
<br/>
<div align="center">
  <img width="380px" src="https://raw.githubusercontent.com/stateful/awesome-vscode-extension-utils/main/.github/assets/logo.png">
</div>
<br/>
<div align="center">

A curated list of delightful [Visual Studio Code](https://code.visualstudio.com/) utilities to build awesome VS Code extensions and resources. For more awesomeness, check out [awesome](https://github.com/sindresorhus/awesome).

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

</div>
<br/>

# Table of Contents

- [Table of Contents](#table-of-contents)
- [Official](#official)
- [Data & State Management](data--state-management)
- [Component Libraries](#component-libraries)
- [Testing](#testing)
- [Logging](#logging)
- [Telemetry](#telemetry)
- [Blog Posts](#blog-posts)
- [Contribute](#contribute)

# Official

- [Official website](https://code.visualstudio.com/)
- [Source code](https://github.com/microsoft/vscode) on GitHub
- [Releases (stable channel)](https://code.visualstudio.com/download)
- [Releases (insiders channel)](https://code.visualstudio.com/insiders)
- [Monthly iteration plans](https://github.com/Microsoft/vscode/issues?utf8=%E2%9C%93&q=label%3Aiteration-plan+)

# Data & State Management

Packages that help extension developer to manage application states and data flow.

- [Tangle](https://github.com/stateful/tangle) - JavaScript state synchronization and event handling for various of different sandbox environments, e.g. worker threads, web workers, iframes, Visual Studio Code Webviews etc

# Component Libraries

Theme packages that help to build awesome VS Code extension UIs.

- [Webview UI Toolkit for Visual Studio Code](https://github.com/microsoft/vscode-webview-ui-toolkit) - A component library for building webview-based extensions in Visual Studio Code
- [VS Code Webview Elements](https://www.npmjs.com/package/@bendera/vscode-webview-elements) - Web component library for developing Visual Studio Code extensions

# Testing

Packages that help you to test your extension.

- [WDIO VSCode Service](https://github.com/webdriverio-community/wdio-vscode-service) - a port of the VSCode Extension Tester framework into WebdriverIO
- [VSCode Extension Tester](https://github.com/redhat-developer/vscode-extension-tester) - Framework for simulating user interactions with VS Code and its extensions via Webdriver
- [VSCode Test](https://github.com/microsoft/vscode-test) - Testing utility for VS Code extensions

# Logging

Packages for logging and debugging.

- [VSCode-Logging](https://www.npmjs.com/package/@vscode-logging/logger) - A Logging Library for VSCode Extension

# Telemetry

Packages that help extension to identify usage patterns and basic telemtry.

- [VS Code Extension Telemetry](https://github.com/Microsoft/vscode-extension-telemetry) - Node module to help VS Code extensions send telemetry using application insights
- [VS Code Telemetry](https://github.com/stateful/vscode-telemetry) - Wrapper around the original telemetry package that helps sending events across extension host and webview environments

# Blog Posts

A set of useful blog post related to VSCode extension development.

- [The GitHub Action You Need to Publish VS Code Extensions](https://www.stateful.com/blog/the-github-action-you-need-to-publish-vscode-extensions) - In this blog post we’d like to share how Stateful releases its Marquee extension to the VS Code Marketplace and OpenVSX Registry through GitHub Actions
- [A Complete Guide to VS Code Extension Testing](https://www.stateful.com/blog/a-complete-guide-to-vs-code-extension-testing) - Most VS Code extensions in the marketplace have minimal testing, if any at all. In this blog post you will learn how to test your VS Code extension from end to end using WebdriverIO.

# Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

---

<p align="center"><small>Copyright 2021 © <a href="http://stateful.com/">Stateful</a> – MIT License</small></p>
