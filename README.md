# knizeciplane.eu

Stránka **knizeciplane.eu** = jen rezervace Previo pro Penzion Hájenka, Knížecí Pláně (lišta → Previo → video → patička), vzhled jako knizeciplane.cz.

- `index.html` = na serveru Active24 `~/knizeciplane.eu/www/eu-rezervace.html` (proxy podle hostu ho servíruje na knizeciplane.eu).
- Jazyk `?lang=cs|de|en` (texty stránky + jazyk Previo).
- Nasazení: lokálně cs/de/en × 390/900/1440 → `scp` na server → readback `md5` → sondy `knizeciplane-cockpit/checks/run-all.sh` (check-07, check-16).
- Provozní dokumentace: repo `knizeciplane-cockpit`.
