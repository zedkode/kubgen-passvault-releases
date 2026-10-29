# KubGen PassVault — versiuni

Aici stau doar versiunile publicate ale KubGen PassVault (Dohot Studio), nu codul sursă.

Fiecare release conține:
- pachetele pentru Linux: `.deb` (Ubuntu, Debian, Mint), `.rpm` (Fedora), `.pkg.tar.zst` (Arch, CachyOS);
- aplicația Android: `kubgen-passvault-<versiune>.apk`;
- `latest.json` (versiunea, fișierele, dimensiunile, SHA-512) și `latest.json.sig`, semnătura hibridă
  Ed25519 + ML-DSA-87 a lui `latest.json`.

Actualizările automate (`kpv-updater` pe calculator, aplicația de pe telefon) citesc ultimul release de aici,
verifică semnătura cu cheia de release din aplicație și apoi SHA-512 al fișierului. Un fișier sau un feed care nu e
semnat cu acea cheie e refuzat; cine controlează acest repo poate doar opri actualizările, nu le poate falsifica.

Software proprietar. Copyright © 2026 Dohot Studio, toate drepturile rezervate.
