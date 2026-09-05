# Contributing

Bug reports and verified key mappings are welcome.

1. Test on a physical Bauhn AIBBTS-0826-K.
2. State whether you used the USB receiver or Bluetooth.
3. Describe the printed legend, key combination, expected output and actual
   output.
4. Keep changes to the `.klc` source reviewable; do not commit generated DLL or
   installer files outside a tagged release.

Before a release, validate and test the source in Microsoft Keyboard Layout
Creator and complete `TESTING.md`. Generated installers should be built from the
tagged source and their SHA-256 hashes published in the release notes.
