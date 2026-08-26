# GD32 Wireless Resources

This page provides an overview of wireless-related repositories under the GigaDevice-GD32-MCU organization.

These repositories cover Wi-Fi and Bluetooth/BLE development for GD32 wireless MCUs, including native SDK development, Arduino development, development tools, and PlatformIO-based workflows.

## Repositories

| Repository | Description |
|---|---|
| [**GD32VW55x_WiFi_BLE_SDK**](https://github.com/GigaDevice-GD32-MCU/GD32VW55x_WiFi_BLE_SDK) | **GD32VW55x Wi-Fi & BLE SDK** — The native software development kit for GD32VW55x wireless MCUs. It provides the core SDK, hardware abstraction and drivers, wireless protocol support, configuration components, build-related tools, and application examples. It is intended for native development of embedded IoT applications based on Wi-Fi 6 and Bluetooth LE 5.2, and provides the underlying software resources for developing and integrating wireless functionality on GD32VW55x devices. |
| [**arduino-gd32w**](https://github.com/GigaDevice-GD32-MCU/arduino-gd32w) | **Arduino Core for GD32W** — An Arduino Core and board support package for GD32W series wireless MCUs. It brings GD32W development into the Arduino ecosystem, allowing developers to build, compile, and upload applications using familiar Arduino APIs and development workflows. The repository supports Arduino IDE and VSCode-based development and includes examples covering Wi-Fi and other commonly used peripherals. It is mainly intended for developers who prefer a simplified Arduino-based development experience. |
| [**gd32w-tools**](https://github.com/GigaDevice-GD32-MCU/gd32w-tools) | **GD32W Development Tools** — A release repository for the development tools required by GD32W software development. It provides packages such as the GD32W toolchain and OpenOCD, which are used for compiling, flashing, and debugging applications. These tools serve as supporting infrastructure for GD32W Arduino and PlatformIO development workflows, rather than being a standalone application framework or SDK. |
| [**pio-projects-gd32w**](https://github.com/GigaDevice-GD32-MCU/pio-projects-gd32w) | **PlatformIO Projects for GD32W** — A PlatformIO project workspace for GD32W wireless MCUs. It provides project templates, configuration files, and application examples for developing GD32W applications within the VSCode + PlatformIO ecosystem. The projects cover both Arduino-based and native SDK-based development approaches, making this repository useful for developers who want to manage GD32W projects through PlatformIO while using either the Arduino framework or the native SDK. |

## Purpose

This page is intended to provide a centralized entry point for GD32 wireless resources under the GigaDevice-GD32-MCU organization. It helps developers identify the appropriate repository based on their development approach, such as native SDK development, Arduino development, PlatformIO-based development, or GD32W development tool usage.

---

# GD32 无线资源

本页面用于汇总 GigaDevice-GD32-MCU 组织下与无线功能相关的仓库。

目前主要覆盖 GD32 无线 MCU 的 Wi-Fi、Bluetooth/BLE、原生 SDK、Arduino、开发工具以及 PlatformIO 等开发方向，为不同开发方式提供统一的仓库检索入口。

## 仓库列表

| 仓库 | 说明 |
|---|---|
| [**GD32VW55x_WiFi_BLE_SDK**](https://github.com/GigaDevice-GD32-MCU/GD32VW55x_WiFi_BLE_SDK) | **GD32VW55x Wi-Fi & BLE SDK** —— 面向 GD32VW55x 无线 MCU 的原生软件开发套件，提供核心 SDK、硬件抽象与驱动、无线协议支持、配置组件、构建相关工具以及应用示例。该仓库主要用于基于 GD32VW55x 的原生无线应用开发，为 Wi-Fi 6 和 Bluetooth LE 5.2 嵌入式 IoT 应用提供底层软件支持和完整的开发资源。 |
| [**arduino-gd32w**](https://github.com/GigaDevice-GD32-MCU/arduino-gd32w) | **GD32W Arduino Core** —— 面向 GD32W 系列无线 MCU 的 Arduino Core 和开发板支持包，将 GD32W 开发能力接入 Arduino 生态。开发者可以使用熟悉的 Arduino API 和开发流程完成应用编译、下载与开发，同时支持 Arduino IDE 和基于 VSCode 的开发方式，并提供 Wi-Fi 及其他常用外设相关示例。该仓库更适合希望采用 Arduino 开发模式、降低底层开发复杂度的用户。 |
| [**gd32w-tools**](https://github.com/GigaDevice-GD32-MCU/gd32w-tools) | **GD32W Development Tools** —— GD32W 开发工具发布仓库，主要提供 GD32W 开发流程所依赖的工具包，包括 Toolchain、OpenOCD 等。相关工具用于应用程序的编译、下载、烧录和调试，并作为 Arduino 和 PlatformIO 开发流程的基础工具支持。该仓库本身主要负责开发工具的提供，而不是提供完整的应用开发框架或无线 SDK。 |
| [**pio-projects-gd32w**](https://github.com/GigaDevice-GD32-MCU/pio-projects-gd32w) | **GD32W PlatformIO Projects** —— 面向 GD32W 无线 MCU 的 PlatformIO 工程工作区，提供项目模板、配置文件以及应用示例。开发者可以在 VSCode + PlatformIO 环境下管理和构建 GD32W 项目，同时支持基于 Arduino Framework 和原生 SDK 的开发方式。对于希望使用 PlatformIO 统一管理工程、依赖和构建流程的开发者，该仓库可以作为项目模板和参考入口。 |

## 说明

本页面可以方便开发者根据实际开发方式快速检索和定位 Wi-Fi、Bluetooth/BLE、Arduino、PlatformIO 以及 GD32W 开发工具相关资源。

后续新的 GD32 无线相关仓库会继续添加到此列表中，保持无线开发资源的集中管理和便捷检索。
