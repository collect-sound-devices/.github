# collect-sound-devices and its applications

The ***Collect Sound Devices*** domain (*collect-sound-devices* bundle) is about
discovering and observing sound devices on end-point PCs (Windows and Linux) and
collecting / updating them in a central registry.

The ***Collect Sound Devices*** is a typical end-point monitoring systems

- *Device Repository Server (C#)*, [audio-device-repo-server](https://github.com/collect-sound-devices/audio-device-repo-server/).<br>
- *Audio Device Repository Client(React/Next/TS)*, [list-audio-react-app](https://github.com/collect-sound-devices/list-audio-react-app/), deployed on Vercel at https://list-audio-react-app.vercel.app
- *Windows Sound Engine Module (C++/Go)* and *Windows Sound Scanner (Go)* [win-sound-engine](https://github.com/collect-sound-devices/win-sound-engine) and [win-sound-scanner-go](https://github.com/collect-sound-devices/win-sound-scanner-go)
- *Linux Sound Scanner (C++)*, [linux-sound-scanner](https://github.com/collect-sound-devices/linux-sound-scanner)
- *RabbitMQ To RestAPI Forwarder (C#)*, [rmq-to-rest-api-forwarder](https://github.com/collect-sound-devices/rmq-to-rest-api-forwarder)
- Alternative *Kafka To RestAPI Forwarder (C#)*, [kafka-to-rest-api-forwarder](https://github.com/collect-sound-devices/kafka-to-rest-api-forwarder)

## License

The collect-sound-devices is licensed under the terms of the [MIT License](../LICENSE).

## Contact

Eduard Danziger

[https://github.com/eduarddanziger](https://github.com/eduarddanziger)

[eduard.danziger@gmx.de](mailto:eduard.danziger@gmx.de)
