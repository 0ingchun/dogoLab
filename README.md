<p align="right">
  <a href="README.md">
    <img src="https://img.shields.io/badge/Switch to-English-blue" alt="Switch to English">
  </a>
</p>

# dogoLab：开源电刺激设备

<p align="center">
  <img alt="banner" src="images/dogoLab_shocker_c3_version1_3D.png" width="600">
</p>
<p align="center">
  一个用于研究，DIY与可穿戴应用的电刺激平台
</p>

---

## 👋 欢迎来到dogoLab！

首先，感谢你的到来！
欢迎你了解 **dogoLab Shocker** —— 一个专为DIY爱好者，研究人员、设计者与开发者打造的 **开源电刺激平台**。

---

## 🚩 功能特色

*  **dogoLab 设备** 为**开放系统**，用户可以编程或调用接口**修改任意波形**或实现**闭环控制**
* 板载 **IMU 传感器（BMI270）**
* 提供 **双向（交流）刺激输出**，可控制同一肌肉**收缩**和舒张
* 内置 **硬件限流与隔离机制**，确保使用**安全**
* 多种控制方式，**USB 有线**，**WiFi & Bluetooth 无线**
* 开发简单，**Arduino编程库demo**，**WebUI遥控调参面板**

---

## 🧠 硬件设计

为了帮助你快速理解 **dogoLab Shocker 的硬件结构与信号流程**，

👉 [硬件模块 使用指南](hardware/README.md)

---

## 📚 固件与SDK库

若你想了解如何使用 SDK 以及内置库函数，请访问：

👉 [SDK & 软件驱动库 使用指南](software/README.md)

---

## 🚀 快速上手 <a name="installation"></a>

> （本节将稍后更新硬件连接方法与 SDK 安装教程）

1. 克隆项目仓库

   ```bash
   git clone https://github.com/0ingchun/dogoLab.git
   cd openTENS
   ```

2. 获取硬件👉 [硬件模块 使用指南](hardware/README.md)

3. 烧录固件👉 [SDK & 软件驱动库 使用指南](software/README.md)

---

## ⚠️ 安全说明

在组装或使用 dogo 硬件前，请务必阅读

👉 [安全与免责声明（SAFETY_NOTICE.md）](SAFETY_NOTICE.md)

---

## ⚠️ 免责声明

- 軟體內所有網頁內容（包括可能存在的付費項目），均与整活者無任何關聯！

- 軟體圖標与開發設計歸项目设计者所有，有關一切禁止商用与公共場合傳播。

- 軟體內容僅供實踐學習使用，使用時請遵守當地法律法規，并自覺在24小時內刪除有關違規內容。

- 请遵守该项目的开源协议

- 下載此项目或使用此项目下的硬件或軟體默認遵守以上內容
---

## 👨‍🔬 谁在开发 dogoLab？

dogoLab
by 0ingChun
Copyright (c) 2025

> ### **版權信息 Copyright information**

版權所有 (c) 2025 [0ingChun](https://github.com/0ingchun)，保留所有權力。

Copyright (c) 2025 [0ingChun](https://github.com/0ingchun), All rights reserved.

---

## 开源协议

> ### **開源協議 Open source license**

硬件原理图和 PCB 设计在 **Apache 2.0** 许可下发布。

Hardware schematics and PCB designs are released under the **Apache 2.0**.

固件和软件在 **Apache 2.0** 许可证下发布。

Firmware and software are released under the **Apache 2.0** License.

---

AD TIME~

## 🧭 相关开源项目

**dogoLab**的**电刺激功能模组**基于**openTENS**实现

[**openTENS - 开源的电刺激模块**](https://github.com/0ingchun/openTENS)

<p align="center">
  <img src="images/AC_TENS_version2_3D.png"  width="250">
</p>

---