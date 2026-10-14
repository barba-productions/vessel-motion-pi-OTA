# Vessel Motion Pi OTA

Public application-update artifacts for Vessel Motion Pi.

Devices download `stable/manifest.json` only when a user starts an update from
the dashboard. The manifest points to a versioned ARM64 release archive and
provides its byte size and SHA-256 digest.

This repository updates the Vessel Motion application only. Raspberry Pi OS
packages and Raspberry Pi EEPROM updates are managed separately.
