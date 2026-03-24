## v2.2.0 - 2026-03-23
- Added graceful sound unmute on addon exit: registered `PLAYER_LOGOUT` event at
  file-load time so WoW's default level-up sound is always unmuted on logout or
  UI reload, preventing permanently muted sounds if the addon is disabled or
  unloaded mid-session
- `UnmuteDefaultLevelUpSound()` now fires unconditionally on logout (no
  `enabled` guard), ensuring the mute state is never stuck between sessions

## v2.1.9
- Updated interface versions in TOC to support latest WoW clients

## v2.1.8
- Re-added Vanilla TOC (SRLU_Vanilla.toc)

## v2.1.7
- Added support for multiple WoW clients via single consolidated TOC

## v2.1.6 - TOC BUMP

## v2.1.1
- Simplified command structure with direct sound selection (`/srlu high`, `/srlu med`, `/srlu low`)
- Persistent settings via SavedVariables
- Multi-language support (English, Russian, German, French, Spanish)
- Extensive error handling and pcall protection
- Professional welcome message with first-run community message
