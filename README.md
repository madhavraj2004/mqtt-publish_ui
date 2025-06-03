# MQTT Publisher and Subscriber UI

This is a simple web-based MQTT Publisher and Subscriber interface built with HTML and JavaScript using the [Eclipse Paho MQTT JavaScript client](https://www.eclipse.org/paho/index.php?page=clients/js/index.php). It allows users to publish messages to an MQTT topic and subscribe to topics to receive messages—all from the browser.

## Features

- **Connects automatically** to a public MQTT broker (HiveMQ).
- **Publish** messages to any MQTT topic.
- **Subscribe** to any topic and view incoming messages in real time.
- Simple, clean UI with responsive design.

## How It Works

- **Broker:** Uses [HiveMQ's public broker](https://www.hivemq.com/public-mqtt-broker/) at `wss://broker.hivemq.com:8000/mqtt`.
- **Client:** Each session uses a random client ID.
- **Publishing:** Enter a topic and message, then click "Publish Message" to send.
- **Subscribing:** Enter a topic and click "Subscribe" to start receiving messages.

## Getting Started

1. **Clone or download** this repository.

2. **Open the HTML file** directly in your browser (no backend/server needed):
    ```
    mqtt-publish_ui/index.html
    ```

3. **Use the interface:**
   - Enter a topic and message to publish.
   - Enter a topic to subscribe and start receiving messages.

## Example

![Screenshot](screenshot.png)

## Dependencies

- [Eclipse Paho MQTT JavaScript Client](https://cdnjs.cloudflare.com/ajax/libs/paho-mqtt/1.0.0/mqttws31.min.js) (loaded via CDN)

## Customization

- You can change the broker URL or add authentication if needed by editing the `brokerUrl` variable in the script section.
- All logic is contained in the HTML file; no additional setup required.

## License

This project is provided under the [MIT License](LICENSE).

---

Made by madhav
