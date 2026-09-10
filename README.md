# Supero-GX
Supero GX — Beta Kit 1.1.0 Changelog
-- Browser Core
Custom borderless window with native drag (title bar)
Double-click title bar to maximize/restore
Windows Aero Snap (drag to edges to snap left/right/maximize)
Double-buffered form, content host, and title bar (white flash fix)
Custom right-click context menu that closes when clicking elsewhere
Hamburger menu auto-closes when clicking outside
Tab system with close/add, middle-click close
Keyboard shortcuts: Ctrl+T (new tab), Ctrl+W (close tab), Ctrl+Shift+T (reopen tab)
Back/Forward/Reload/Stop navigation buttons
Loading spinner on tab bar
Auto-focus address bar after navigation

-- Appearance
4 themes: Classic (dark), Interstellar (deep blue), Metamorphic (neutral grey), Aurora (slate/teal)
Cat Co theme removed from earlier builds
Light/Dark mode toggle with full UI color swap (titles, bars, sidebar, buttons, backgrounds)
Accent color picker
Google-style search bar with hover scale effect
Speed dial tiles with hover float + scale + shadow
Google Lens overlay (URL search, file upload, drag & drop)
Tab session save/restore across restarts

-- Pages
supero://home — speed dial grid, clock, Google search bar, Google Lens button
supero://settings — full Opera GX-style settings with sidebar navigation (Appearance, Features, Sync, Downloads, System, Startup, Developer, Passwords, Reset)
supero://history — browsing history
supero://account — Firebase account creation, login, logout, profile display
supero://passwords-vault — view all saved passwords after account password verification, 1-minute inactivity auto-lock
supero://help — help page
Sync/VPN profile popups navigate to correct settings sub-pages

-- Sync & Accounts
Firebase Auth REST API (create account, login, logout, password reset)
TLS 1.2 fix for .NET 4.0
SyncToFirebase / PullFromFirebase for bookmarks, speed dial, passwords, history, open tabs, settings
Account password saved locally for vault access

-- Password Manager
Password capture via injected JS (form submit, button click with 800ms debounce, 4s fallback)
Password save popup (right side, can't click away, Decline/Add buttons, "View saved passwords" link)
Password autofill picker dropdown on login pages (native setter for React compatibility)
Password vault with custom confirm dialogs replacing browser confirm()

-- Installer
Self-contained installer with all resources embedded (exe, DLLs, icon, manifest)
Start menu shortcut creation
Windows registry uninstaller entry
Simple basic Windows dialog UI (no custom styling)
Uninstaller included in Release folder
