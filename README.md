# Unicodem k bezpečnosti #

## Souhrn ##

Myslet na všechny ty podivné znaky z cizích světů má smysl nejen kvůli Japoncům a Klingonům. Správné zacházení se znakovými sadami nepřispívá jen spokojenosti uživatelů, ale může být i zásadní pro bezpečnost aplikace. Podíváme se, jaké nástrahy číhají v unicodových rovinách a v pohořích jiných kódování. Na ty technické, způsobené podstatou daného kódování, i na ty přirozené &ndash; lidské, vycházející z významové složky znaků. Některé věci jdou vyřešit jednoduše, povíme si jak. U jiných zkusíme najít kompromis mezi bezpečností a použitelností.

## Osnova ##

Co bych chtěl zmínit?

### Technické potíže ###

* Neunicodová kódování
  * Část znaku může být nechtěně ASCII – SQL injection
  * Nejasný začátek a konce znaku – vyhledávání (Shift-JIS)
* Chybná podpora
  * Převod na otazníčky
  * Ztrácení řetězců v MySQL
  * Vykreslování (sanskrt)

### Lidské potíže ###

* Sjednocení znaků
  * Skládání
  * Převody mezi abecedami
* Obrazová podoba
  * Neviditelné znaky
  * Podobné znaky
  
## Snímky ##

## Tvůrce ##

Tuto přednášku pro [PyCon CZ 2019][PyCon] stvořil [Glutexo].

## Licence ##

Dělejte si s tím, co chcete.

[PyCon]: https://cz.pycon.org/2019/programme/talks/31/#main
[Glutexo]: mailto:glutexo@icloud.com
