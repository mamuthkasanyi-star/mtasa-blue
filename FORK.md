# RP kliens – Multi Theft Auto: San Andreas fork

Ez a [multitheftauto/mtasa-blue](https://github.com/multitheftauto/mtasa-blue) forkja
egy magyar LAN roleplay szerverhez. Licenc: GNU GPL v3 (lásd LICENSE), az eredeti
szerzői jogi megjegyzések változatlanok.

Módosítások az eredetihez képest (a https://wiki.multitheftauto.com/wiki/Forks és a
`Shared/sdk/version.h` útmutatója szerint):

- `MTASA_VERSION_TYPE` = `VERSION_TYPE_UNSTABLE`
- kliens: `fork-support/netc.dll` (utils/buildactions/install_data.lua)
- Nightly build konfiguráció (win-build.bat, linux-build.sh, CI)
- termék registry/adatmappa név: „RP Kliens MTA” (ne ütközzön a hivatalos MTA-val)
- a CI csak a win32 klienst és a linux x64 szervert fordítja

A szerveren: `<disableac>5,6,21</disableac>`, fejlesztői net.so.
