# 基于NFC技术的身份验证门禁系统

🌍 *[English](README-EN.md) ∙ [简体中文](README.md)*

一种基于NFC技术的身份验证门禁系统，利用移动终端设备的便携性和智能化特点，通过NFC技术实现快速、安全的身份验证，并通过物联网技术管理身份信息，提高安全性和灵活性。

## 项目仓库及主要技术

### 门禁硬件 [[AccessControlSystem-Hardware](https://github.com/YukiIsait/AccessControlSystem-Hardware)]

- Arduino
- STM32
- PN532
- W5500
- LCD1602 (PCF8574)
- AT24C02
- 舵机

### 管理平台客户端 [[AccessControlSystem-ManagementPlatform](https://github.com/YukiIsait/AccessControlSystem-ManagementPlatform)]

- TypeScript
- Electron
- Vue.js (Vue Router, Vuex)
- Vuetify

### 安卓客户端 [[AccessControlSystem-AndroidClient](https://github.com/YukiIsait/AccessControlSystem-AndroidClient)]

- Kotlin
- Jetpack Compose
- Lifecycle ViewModel
- Retrofit

### 服务端 [[AccessControlSystem-Server](https://github.com/YukiIsait/AccessControlSystem-Server)]

- Kotlin
- Spring Boot (Spring Web, Spring Security, Spring Data JPA)
- MySQL
- JWT

## 开源许可

本项目开源于MIT许可证，详见[LICENSE](LICENSE.md)文件。
