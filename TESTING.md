# Physical-keyboard test checklist

Complete this checklist on Windows with the Bauhn AIBBTS-0826-K before making
the first stable release.

## Identity

- [ ] Model on underside is `AIBBTS-0826-K`
- [ ] Aldi product code is `860396`
- [ ] Test USB receiver
- [ ] Test Bluetooth (if supported by your variant)

## Printed character keys

Open Notepad and verify that every result matches the legend on the pressed key.

- [ ] Number row without modifiers: ``1234567890-=`
- [ ] Number row with Shift: `~!@£$%^&*()_+`
- [ ] AltGr+3: `#`
- [ ] AltGr+4: `€`
- [ ] Punctuation without modifiers: `[]\;',./`
- [ ] Punctuation with Shift: `{}|:"<>?`
- [ ] All A–Z letters, lower- and uppercase

## Behaviour and shortcuts

- [ ] Ctrl+C, Ctrl+V, Ctrl+X and Ctrl+Z work
- [ ] Windows shortcuts still work
- [ ] Function/media keys retain their hardware behaviour
- [ ] Arrow, Home, End, Page Up, Page Down and Delete work
- [ ] No quote or accent key behaves as a dead key

## Removal test

- [ ] The layout can be removed in Windows language options
- [ ] The package uninstaller removes it cleanly

Record failures in a GitHub issue with the connection method and exact key
combination.
