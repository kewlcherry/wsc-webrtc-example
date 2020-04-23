# wsc-webrtc-example

## Connect a WebRTC stream to Wowza Streaming Cloud

This package includes an HTML example of how to use the WebRTC HTML5 browser capability with the Wowza Streaming Cloud™ service. Session information (SDP data) is exchanged between the browser and Wowza Streaming Cloud using a WebSocket connection with JSON-formatted data. The current implementation is very simple. This functionality is only supported by browsers that support the WebRTC API.

## Contents

- [About WebRTC](#about)
- [Examples](#examples)
- [Contact](#contact)
- [License](#license)

<a name="about"></a>

## About WebRTC

Web Real-time Communication (WebRTC) is an open source project to enable real-time communication of audio, video, and data in web browsers and native apps. WebRTC is designed for peer-to-peer connections but includes fallbacks in case direct connections fail. Encryption is mandatory for WebRTC streams, so you must host the example on a web server utilizing SSL encryption.

## Examples

The example files can be used to publish a WebRTC stream to Wowza Streaming Cloud. In order for the example to work properly, the transcoder's stream extension must be set to .json. Additionally, the files must be hosted on a webserver utilizing SSL encryption.

For more information on how to implement this example, see the following articles:

* [Connect a WebRTC stream to Wowza Streaming Cloud](https://www.wowza.com/docs/connect-a-webrtc-stream-to-wowza-streaming-cloud)
* [Connect a WebRTC stream to Wowza Streaming Cloud using the Wowza Streaming Cloud REST API](https://www.wowza.com/docs/connect-a-webrtc-stream-to-wowza-streaming-cloud-using-the-wowza-streaming-cloud-rest-api)

## Contact

Wowza Media Systems™, LLC

Wowza Media Systems provides developers with a platform to create streaming applications and solutions. See the [Wowza Developer Portal](https://www.wowza.com/resources/developers) to learn more about our APIs and SDKs.

## License

This code is distributed under the [BSD 3-Clause License](https://github.com/WowzaMediaSystems/wsc-webrtc-example/blob/master/LICENSE.txt).
