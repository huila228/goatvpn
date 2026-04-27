# VPN transparency

This repository contains the public transparency files for my VPN setup.

## Components

- Client: Amnezia VPN
- Core: Xray-core
- Panel: 3x-ui / custom setup

## What is included

- Example server config without secrets
- Description of server architecture
- Links to open-source components

## What is not included

- Private keys
- UUIDs
- Admin passwords
- User data


servers architecture:
iPhone
  ↓ encrypted VLESS/Reality traffic
RU server :443
  ↓ same encrypted bytes, just forwarded
EU server :443
  ↓ тут уже Xray проверяет UUID/Reality/etc
Internet
