# Project description

![BonePic](.resources/boneIO_v0.2render.png?raw=true)
![BoneDiagram](.resources/boneio.drawio.png?raw=true)

`BoneIO` is a compact IO controller for home automation. Main features of this controller are

- Compact size (27x11x6)cm - 15 DIN modules
- DIN rail compatibility
- Low price
- Open HSP (See below)

# Technical details of v0.2

![InputBoard](.resources/input_board_text.png?raw=true)

- 52 digital inputs
- 7 analog to digital converters
- i2c
- rs485
- OLED display
- user switch
- 24V PSU input
- ADC VDD output
- 12-48V external PSU for digital inputs
- jumper to switch between internal and external PSU for inputs
- jumper to switch between vcc and gnd input control

![RelayBoard24x16](.resources/relay_board_24x16A_text.png?raw=true)

- 24 relays (230V/16A) max current 5A* (10A* tinned traces, 16A* bridged 1,5 mm²) *everything needs to be verified
- temp sensor

![RelayBoard32x5](.resources/relay_board_32x5A_text.png?raw=true)

- 32 relays (230V/5A)
- temp sensor

# Open HSP

`BoneIO` is an Open HSP initiative where everything is open on [GPL-3.0 License](https://github.com/maciejk1984/boneIO/blob/main/LICENSE)

- H (Hardware) stands for projects of electronic boards which you can print yourself
- S (Software) stands for ready to use firmware you can use on printed hardware
- P (Printables) stands for cases and other plastic elements you can print on a 3D printer and use with our hardware

With all elements in place, you can assemble a complete device. You can use it as-is or fork and modify it for your needs.

# Contribution

If you want to contribute to the project here are the rules:

1. First watch this short training: [How to use repo](https://www.youtube.com/watch?v=aY7B_t2UZy4)
2. When you have something to discuss first check out our [Team chat](https://discord.gg/PsrXEz9CBp)
3. When you have a specific problem/feature to report add new [issue](https://github.com/maciejk1984/boneIO/issues). `Remember to report single topic in one issue`. If you have complex topic try split it to more **precise** topics.
4. When you want change something in the repository use your **Fork** and make new **Pull Request** (See [Working with repository](.docs/github.md) (Polish))
5. You can also monitor our [Facebook group](https://www.facebook.com/groups/boneio)

# Documentation

- [Working with repository](.docs/github.md) (Polish)
- Youtube
  - [Project introduction](https://www.youtube.com/watch?v=_EIppBDZWvk) (Polish)
  - [Case introduction](https://www.youtube.com/watch?v=QjhMvNn7mG0) (Polish)
  - [Project status - 17.10.2021](https://www.youtube.com/watch?v=6J2S1L4vNMw) (Polish) 


# Photos of v0.1

![Github](.resources/bone_relays.jpg?raw=true)

![Github](.resources/bone_view.jpg?raw=true)

![Github](.resources/bone_inputs.jpg?raw=true)

![Github](.resources/bone_din.jpg?raw=true)

