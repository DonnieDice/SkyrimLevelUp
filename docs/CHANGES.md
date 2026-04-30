# v3.0.0 - 2026-04-30

## Changes

- **Migrated to RGX-Framework**: Added `RequiredDeps: RGX-Framework` to TOC. Core logic now uses `RGX:GetSound()`, `RGX:RegisterEvent()`, and `RGX:RegisterSlashCommand()` — eliminating duplicated boilerplate.
- **RGXSound handle**: Sound playback, variant management, mute/unmute, settings, and welcome message are now handled by the RGXSound module in RGX-Framework.
