# team_management

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## OpenSSL Keystore for Signing
```bash
keytool -genkey -v -keystore ./key.jks -storetype JKS -keyalg RSA -keysize 2048 -validity 10000 -alias key
openssl base64 -A -in ./key.jks
```