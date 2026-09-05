# Bauhn AIBBTS-0826-K Windows keyboard layout

An open-source Windows keyboard layout for the Bauhn AIBBTS-0826-K wireless
keyboard sold by Aldi UK (product code 860396, dated 08/2026).

(Please feel free to add layout files for other OSes - e.g. Linux and MacOS.)

The keyboard uses a US/ANSI physical arrangement but prints several UK and
European symbols. No matching built-in Windows layout or model-specific layout
download has been found.

## Intended mapping

This layout keeps ordinary US/ANSI QWERTY punctuation and adds the printed
currency/symbol layer:

| Key | No modifier | Shift | AltGr |
| --- | --- | --- | --- |
| `2` | `2` | `@` | — |
| `3` | `3` | `£` | `#` |
| `4` | `4` | `$` | `€` |
| Apostrophe | `'` | `"` | — |
| Grave | `` ` `` | `~` | — |

Everything else follows the standard US/ANSI layout.

## Build on Windows

1. Download and install [Microsoft Keyboard Layout Creator 1.4][msklc].
2. Open `windows/bauhn-aibbts-0826-k.klc` in MSKLC.
3. Select **Project → Validate Layout**.
4. Select **Project → Test Keyboard Layout** and run the checks in
   `TESTING.md`.
5. Select **Project → Build DLL and Setup Package**.

## Installation

1. Download ./windows/bauhn826/ or see build instructions above.
2. Run setup.exe
3. After installation, add **Bauhn AIBBTS-0826-K** under Windows language keyboard
options and remove other layouts if accidental switching is a nuisance.
4. **Logout, and back in, or reboot** Windows' language system is fairly broken!

## Why a custom layout?

Windows' US layout puts `#` on Shift+3 and has no `£` or `€` layer. The UK
layout provides `£`, but moves `@`, `"`, `#`, `~`, and backslash to positions
that do not match this ANSI keyboard. This source starts with US/ANSI and makes
only the three changes printed on the Bauhn keys.

## Contributing

Reports from other AIBBTS-0826-K owners are especially useful. Please include:

- the model and product code from the underside;
- the operating system;
- the exact key/modifier combination;
- expected and actual output;
- whether the USB receiver or Bluetooth connection was used.

See `CONTRIBUTING.md` for the release process.

## Licence and trademarks

The project is licensed under the MIT Licence. Bauhn and Aldi are trademarks of
their respective owners. This is an independent community project and is not
endorsed by either company.

[msklc]: https://www.microsoft.com/en-us/download/details.aspx?id=102134
