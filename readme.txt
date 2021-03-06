=== Surbma - Magyar WooCommerce ===
Contributors: Surbma
Donate link: https://surbma.hu/wordpress/wordpress-bovitmenyek/
Tags: woocommerce, hungarian, hungary
Requires at least: 3.0
Tested up to: 4.8
Stable tag: 1.0.0
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Hasznos javítások a magyar nyelvű WooCommerce webáruházakhoz.

== Description ==

A WooCommerce a világ és most már Magyarország legnépszerűbb webáruház platformja is. De ez a tény a WooCommerce fejlesztőket nem érdekli annyira, hogy a magyar igényekhez igazítsák a bővítmény bizonyos funkcióit. Szerencsére adnak bőven lehetőséget a módosításokra, de ezekhez az átlag felhasználó nem ért. Ezért hoztam létre ezt a bővítményt, hogy a magyar WooCommerce webáruházak is végre rendben legyenek.

A funkciók folyamatosan bővülnek, de itt a WordPress.org fórumban is lehet új funkciókat kérni.

**A bővítmény eddigi funkciói:**
- A keresztnév és vezetéknév sorrendjének a megfordítása a Pénztár oldalon akkor, ha a cím Magyarország. Ahogy mi szeretjük. :) Mindezt úgy, hogy reszponzív nézetben is jó legyen és a CRM, számlázó programok is tudják értelmezni.
- Megye mező elrejtése. Mert ezt nálunk nem szokás használni, így csak plusz felesleges lépés. De ha valakinek nagyon kell, akkor visszaállítható. Ehhez a wp-config.php fájlba kell ezt a sort megadni: `define( 'SURBMA_MWC_MEGYE' , true );`
- További funkciók hamarosan...

**Szeretnél résztvenni vagy segíteni a bővítmény fejlesztésében?**

Megtalálod a teljes forráskódot a GitHub-on: [https://github.com/Surbma/surbma-magyar-woocommerce](https://github.com/Surbma/surbma-magyar-woocommerce)

**További bővítményeket és projekteket is találsz a GitHub oldalamon:**

[https://github.com/Surbma](https://github.com/Surbma)

Nyugodtan segíthetsz a bővítmények, sablonok és egyéb projektek fejlesztésében.

**Szeretnél többet tudni rólam és a szolgáltatásaimról?**

Nézd meg a weboldalam: [Surbma.hu](https://surbma.hu/)

== Installation ==

1. Töltsd fel a `surbma-magyar-woocommerce` mappát a `/wp-content/plugins/` mappába.
2. Aktiváld a Surbma - Magyar WooCommerce bővítményt a 'Bővítmények' menüpont alatt a WordPress admin felületen.
3. Ennyi az egész. :)

== Frequently Asked Questions ==

= Hol találom a bővítmény beállításait? =

A bővítménynek egyelőre nincsenek beállításai. A felsorolt funkciók a bővítmény aktiválása után automatikusan érvényesek lesznek.

= Nem cserélődtek meg a nevek a Pénztár oldalon. =

Először töröld a szerver oldali és a böngésző gyorsítótárát és frissítsd az oldalt! Győződj meg róla, hogy esetleg más bővítmény nem okoz-e konfliktust! Ha a fordítást módosítottad, az is lehet probléma. Illetve a sablonok is tartalmazhatnak olyan egyedi kódokat, amivel ez a funkció felülírható.

Figyelem! A nevek cseréje csak akkor történik meg, ha Magyarország a választott ország.

= Mit jelent az, hogy Surbma? =

A vezetéknevem visszafelé. ;)

== Changelog ==

= 1.0.0 =

- Első kiadás.
