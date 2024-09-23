# LDK Node Desktop Client

This project is and will be a **Rust-based desktop application** that combines an **on-chain Bitcoin wallet** with a **self-custodial Lightning node**. It's a personal project aimed at showcasing my Rust skills and the **BIP21 Unified QR** implementation I worked on during the **Summer of Bitcoin 2024**.

## Overview

The goal is to build a cross-platform desktop app using Rust and [Tauri](https://tauri.app) for the user interface, allowing users to:

- Manage an **on-chain Bitcoin wallet**.
- Interact with a **self-hosted Lightning node** via the [LDK's LDK Node](https://github.com/lightningdevkit/ldk-node).
- Generate and scan **BIP21 Unified QR codes** that handle both on-chain and Lightning payments in a single QR.

This project will also serve as a practical demonstration of my work on BIP21 Unified QR support, integrating **BOLT11** and **BOLT12** Lightning invoices.

## Features (Planned)

- **On-Chain Bitcoin Wallet**:
    - Create and manage Bitcoin addresses.
    - Send and receive transactions.

- **Lightning Node**:
    - Self-custodial Lightning node functionality using LDK.
    - Open and manage payment channels.

- **BIP21 Unified QR Code**:
    - Generate Unified QR codes for Bitcoin and Lightning payments.
    - Support for both BOLT11 invoices and BOLT12 offers.

- **Desktop UI**:
    - Built using  [Tauri](https://tauri.app)  for a lightweight, cross-platform desktop experience.

## Tech Stack

- **Rust**: The entire application logic will be written in Rust.
- **LDK (Lightning Development Kit)**: To implement the Lightning node functionality.
- **Tauri**: For building the cross-platform user interface.

## Project Status

This is an early-stage personal project. Code and architecture are still in the planning phase.

