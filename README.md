# nol.i18n

Traductions et pluriels CLDR, en pur [Nolc](https://noliae-nolc.s3.gra.io.cloud.ovh.net/nolc-latest-linux-x86_64.tar.gz), sans dépendance.

## Installation

```toml
[dependances]
"nol-i18n" = { git = "https://github.com/Noliae-France/nol-i18n" }
```

## API

`catalogue_neuf(langue)`, `ajoute(cle, traduction)`, `traduit`, `traduit_n` (substitue {n}), `forme_plurielle(langue, n)` (fr: pluriel des 2 ; en: des n!=1), `pluralise(singulier, pluriel, n)`.

## Licence

MIT © 2026 Bastien LANGUEDOC.
