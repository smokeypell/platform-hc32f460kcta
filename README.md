# HUADA HC32F460 Series: development platform for [PlatformIO](https://platformio.org)

The HC32F460 Series of MCUs is a 32-bit MCU based on the ARM Cortex-M4 processor.
It integrates up to 512 KB of Flash memory, and up to 192 KB of SRAM.

These MCUs are somewhat often found in entry level 3D printers, tho development boards are rumored to exist as well.

1. [Install PlatformIO](https://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](https://docs.platformio.org/page/projectconf.html) file:

## Development Version

```ini
[env:myenv]
platform = https://github.com/smokeypell/platform-hc32f460kcta.git
board = hc32f460kcta
...
```

# Configuration

The platform itself contains basically no configuration options.
Everything is configured in the framework packages.
Please refer to [framework-arduino-hc32f46x](https://github.com/smokeypell/framework-arduino-hc32f460kcta) and [framework-hc32f46x-ddl](https://github.com/smokeypell/framework-hc32f460kcta-ddl) for more information.

# Notice

this platform is still in development, and not yet ready for production use.
expect things to break over time.