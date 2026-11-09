NOVA — Roblox client UI / diagnostics
This package contains a NOVA-branded interface build and read-only diagnostic helpers.
Files
`NOVA.lua` — main UI build, with the legacy forced remote drop-pickup path disabled. Drop collection is limited to normal character-touch/physics behavior.
`NOVA-diagnose.lua` — read-only executor/client-reference diagnostics.
`NOVA-world-diagnostics.lua` — read-only client module and world API inspection.
`n4th` — original upstream loader retained for compatibility with the existing repository layout.
Compatibility notes
Internal session/config identifiers such as `__n4thOpus` and `n4thOpus` are intentionally retained so existing settings are not orphaned.
This is a static source edit. It has not been executed inside Roblox or compiled with the Luau compiler in this environment. Test in a private test place first.
Remote spoofing, forced item pickup, inventory manipulation, and server-validation bypasses are not included.
