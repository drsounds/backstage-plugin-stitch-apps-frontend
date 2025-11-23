# Backstage Stitch Apps Plugin

> [!WARNING]
> **Work in Progress**: This plugin is currently under active development. Features and APIs are subject to change.

This Backstage plugin provides the capability to embed HTML5 "stitch" applications directly within a Backstage instance. It is designed to facilitate seamless integration between Backstage and third-party solutions.

## Features

- **Embed HTML5 Apps**: Easily host and display external HTML5 applications within the Backstage UI.
- **Third-Party Integration**: Bridge the gap between Backstage and external tools or services.
- **Bi-directional Communication**: Enables communication between the embedded app and Backstage using `window.postMessage`, allowing for rich interactions and data exchange.

## Communication

The plugin supports a communication protocol based on `window.postMessage`. This allows the embedded "stitch" app to send messages to the Backstage host and receive responses, enabling tight integration with Backstage's context and APIs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
