# Automation-Protocols-Metadata
An update metadata of Automation Protocols (Industrial control system, process automation, building automation, automatic meter reading, and automobile).

### Entry example (main)
```json
{
  "refs": {
    "nmap": "https://nmap.org/nsedoc/scripts/modbus-discover.html",
    "wiki": "https://en.wikipedia.org/wiki/Modbus",
    "wireshark": "https://www.wireshark.org/docs/dfref/m/modbus.html"
  },
  "name": "Modbus",
  "groups": [
    "Process automation protocols",
    "Building automation protocols",
    "Automatic meter reading protocols",
    "Fieldbus"
  ],
  "ports": [
    "502"
  ],
  "info": "Modbus is a data communications protocol originally published by Modicon (now Schneider Electric) in 1979 for use with its programmable logic controllers (PLCs). Modbus has become a de facto standard communication protocol and is now a commonly available means of connecting industrial electronic devices.Modbus is popular in industrial environments because it is openly published and royalty-free. It was developed for industrial applications, is relatively easy to deploy and maintain compared to other standards, and places few restrictions - other than the datagram (packet) size - on the format of the data to be transmitted.\nThe Modbus protocol uses character serial communication lines, Ethernet, or the Internet protocol suite as a transport layer.\nModbus supports communication to and from multiple devices connected to the same cable or Ethernet network. For example, there can be a device that measures temperature and another device to measure humidity connected to the same cable, both communicating measurements to the same computer.\nModbus is often used to connect a plant/system supervisory computer with a remote terminal unit (RTU) in supervisory control and data acquisition (SCADA) systems in the electric power industry. Many of the data types are named from industrial control of factory devices, such as Ladder logic because of its use in driving relays: A single physical output is called a coil, and a single physical input is called a discrete input or a contact.\nThe development and update of Modbus protocols have been managed by the Modbus Organization since April 2004, when Schneider Electric transferred rights to that organization. The Modbus Organization is an association of users and suppliers of Modbus-compliant devices that advocates for the continued use of the technology. Modbus Organization, Inc. is a trade association for the promotion and development of Modbus protocol. - (wikipedia)"
}
```

### Entry example (sub)
```json
{
  "refs": {
    "wireshark": "https://wiki.wireshark.org/Contrib"
  },
  "name": "Crimson V3",
  "groups": [
    "other"
  ],
  "ports": [
    "789"
  ]
}
```

### Integration Example (ics-visualizer)
<img src="https://raw.githubusercontent.com/qeeqbox/ics-visualizer/main/readme/intro.gif" style="max-width:768px"/>

### Notes
- Automation protocols metadata db was compiled using my previous experience with ICS and a lot of great external articles\\researches\\projects (Do not forget to check them out!)

### Resources
wikipedia wireshark nmap and more

### Other Projects
[![](https://github.com/qeeqbox/.github/blob/main/data/social-analyzer.png)](https://github.com/qeeqbox/social-analyzer) [![](https://github.com/qeeqbox/.github/blob/main/data/mitre-visualizer.png)](https://github.com/qeeqbox/mitre-visualizer) [![](https://github.com/qeeqbox/.github/blob/main/data/analyzer.png)](https://github.com/qeeqbox/analyzer) [![](https://github.com/qeeqbox/.github/blob/main/data/chameleon.png)](https://github.com/qeeqbox/chameleon) [![](https://github.com/qeeqbox/.github/blob/main/data/honeypots.png)](https://github.com/qeeqbox/honeypots) [![](https://github.com/qeeqbox/.github/blob/main/data/url-sandbox.png)](https://github.com/qeeqbox/url-sandbox) [![](https://github.com/qeeqbox/.github/blob/main/data/woodpecker.png)](https://github.com/qeeqbox/woodpecker) [![](https://github.com/qeeqbox/.github/blob/main/data/docker-images.png)](https://github.com/qeeqbox/docker-images) [![](https://github.com/qeeqbox/.github/blob/main/data/seahorse.png)](https://github.com/qeeqbox/seahorse) [![](https://github.com/qeeqbox/.github/blob/main/data/rhino.png)](https://github.com/qeeqbox/rhino) [![](https://github.com/qeeqbox/.github/blob/main/data/raven.png)](https://github.com/qeeqbox/raven)
