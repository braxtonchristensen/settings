# settings

Braxton's settings

# Desktop setup

- Install Homebrew: `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
- Install Google Drive: `brew cask install google-drive`
- Rename Google Drive directory: `mv ~/Google\ Drive  ~/drive`
- Start Google Drive directory sync and wait for initial completion
- Run set up script: `. ~/drive/settings/index`

_Most things are taken care of automatically with the set up script ^, but some manual items are needed:_

- iterm2 colors file can be found in dotfiles
- iCloud (disable everything except Find My Mac, Keychain, Photos, and Messages inside iCloud Drive)
- Remove all dock icons
- Dock auto hide (on)
- Menu Bar auto hide (on)
- Login items (`Google Drive`, `Google Photos Backup`, `RescueTime`)
- Text Message Forwarding (on)
- Do Not Disturb scheduled (on, from 11pm-7am), when display is sleeping (on), when mirroring to TVs and projectors (on), allow repeated calls (on), sort order (recents by app)
- Night Shift (scheduled, from sunset to sunrise)
- Find My Mac (on)
- Highlight color (Nova cyan)
- Prevent computer from sleeping automatically when display is off (on)
- Show all filename extensions (on)
- Show warning before changing an extension (off)
- Power adapter, turn display off after (never)
- Default browser (Chrome)
- Security & Privacy control permissions (on)
- Alert sound (glass)
- Alert volume (full)
- Message sound (popcorn)
- Keyboard modifier keys caps lock (escape)
- Correct spelling automatically (off)
- Remove items from the Trash after 30 days (on)
- Keep folders on top when sorting by name (on)
- Garage Band add composer and author (`Perfect Particle`)
- Finder sidebar condense (`Google Drive`, `Downloads`, `AirDrop`)
- WakaTime config (add API key to `~/.wakatime.cfg` or in Atom)
- Chrome extensions (1Password, SiteCop, Grammarly, React DevTools)
- Google safe search (on)
- Google Photos Backup size (`Original`)
- Time Machine backup on external hard drive
- Backups working in background (Google Drive, Google Photos Backup, Time Machine external drives)
