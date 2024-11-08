# Hibaelhárítás (Soundhax)

Ez az oldal hibaelhárítási tanácsokat ad sűrűn előforduló problémákhoz a "Boot9strap telepítése (Soundhax)" oldalhoz, ami az 1.0.0 és 11.3.0 rendszer verziókon használt. Ha nem tudod megoldani a problémád az oldal tanácsai alapján, csatlakozz a [Nintendo Homebrew-hoz Discord-on](https://discord.gg/MWxPgEp) és írd le a problémádat és azt is hogy mi az amit már próbáltál.

## Problémák a Soundhax-szal

:::details Piros/lila/rózsaszín és fehér képernyő a Soundhax futtatása után

Ha a konzol rendszer verziód 9.4.0, 9.5.0, vagy 9.6.0, hibát tapasztalhatsz az universal-otherapp egy régebbi verziójával. Töltsd le a legfrissebb verziót [innen](https://github.com/TuxSH/universal-otherapp/releases/latest).

Ha nem ezeken a firmware verziókon van a konzolod, akkor ez valószínűleg azt jelzi, hogy már van egyedi firmware-ed. Érdemes elvégezned a [CFW ellenőrzését](checking-for-cfw).

:::

:::details "An error has occurred, forcing the software to close..." (fehér üzenet ablak)

Probléma van a `otherapp.bin` fájloddal (nem jó, hiányzik, rossz helyen van vagy sérült). Töltsd le a legutolsó kiadását az [universal-otherapp](https://github.com/TuxSH/universal-otherapp/releases/latest)-nak és rakd az SD kártyád gyökerébe.

:::

:::details "Could not play"

Rossz Soundhax fájlod van a konzolodhoz és a régiódhoz vagy az eszközöd nem kompatibilis a Soundhax-szal. Később, azt, hogy mit kell csinálnod, attól függ, hog milyen verzión van a 3DS-ed jelenleg. Csatlakozz a [Nintendo Homebrew-hoz a Discord-on](https://discord.gg/MWxPgEp) segítségért.

:::

:::details Failed to mount the SD card!

Ha ez sikertelen, próbálkozz egy másik SD kártyával.

:::

## Problémák a SafeB9SInstaller-rel

<!--@include: ./_include/troubleshooting-sb9si-bin.md -->

<!--@include: ./_include/troubleshooting-sb9si-common.md -->

<!--@include: ./_include/troubleshooting-get-help-common.md -->

---

::: tip

Vissza [Boot9strap telepítése (Soundhax)](installing-boot9strap-\(soundhax\))-hoz

:::

<!--@include: ./_include/troubleshooting-return.md -->
