TableWatch

TableWatch je aplikace navržená pro zlepšení zážitku z návštěvy restaurací a kaváren tím, že umožňuje uživatelům vidět aktuální dostupnost míst a rezervovat si stůl předem.

Funkce

Přehled volných a obsazených míst: Uživatelé mohou rychle zjistit, kolik míst je v restauraci nebo kavárně k dispozici a kolik je již obsazených.

Rezervace stolu: Pokud je volný stůl k dispozici, uživatelé mohou jednoduše provést rezervaci přímo v aplikaci.

Dynamická aktualizace dostupnosti: Díky čidelům hmotnosti na židlích je aplikace schopna dynamicky aktualizovat dostupnost stolů v reálném čase. Když se uživatel zvedne z místa, systém počká krátkou prodlevu, než uvolní místo k další rezervaci.

Oznámení o rezervaci: Uživatelé obdrží potvrzení o své rezervaci včetně času a místa.

Jak to funguje

Zobrazení dostupnosti: Po spuštění aplikace uživatelé vidí seznam restaurací a kaváren, které jsou v síti TableWatch. Vedle každého zařízení je zobrazen počet volných a obsazených stolů.

Výběr místa a rezervace: Uživatelé si mohou vybrat konkrétní zařízení a prohlédnout si detaily dostupných stolů. Po výběru počtu osob a času rezervace mohou provést rezervaci.

Dynamická aktualizace: Aplikace neustále sleduje stav stolů pomocí čidelů hmotnosti. Jakmile se uživatel zvedne z místa, aplikace počká krátkou prodlevu a poté aktualizuje dostupnost stolu.

Potvrzení rezervace: Po dokončení rezervace uživatel obdrží potvrzení o své rezervaci včetně podrobností o čase a místě.

TableWatch respektuje soukromí uživatelů a neukládá žádné osobní údaje mimo nezbytné informace pro provedení rezervace. Všechna data jsou šifrována a chráněna proti neoprávněnému přístupu.

Pro přístup k aplikaci a využití všech funkcí je vyžadována registrace.

Zakazník jakmile si sedne, tak na židli bude upevněný váhový senzor, který bude připojen na ESP32.
Aplikace funguje na ESP32, který je připojený na firebase databázi aby se uložilo přihlašení od zakazníka.
To nám v aplikaci umožní vidět stoly, kde zakazníci sedí nebo ne.
Pokud bude místo volné, člověk může jen kliknout a bude mít rezervaci.

Jediný problém s aplikací při vývoji byl FIREBASE od Google.
Udělal jsem webovou aplikaci a databázi.
Napsal jsem kód, tak aby se do aplikace přihlasil člověk jen Jménem a E-mailem viz. prihlaseni.watchtable.html ve složce.
V databázi se ale nic neukazuje, což nechápu, jelikož jsem tam dával kód na propojení Databáze se stránkou.

Na vývoj aplikace byl použit hlavně youtube pro informace a Gifthub.
Inspiroval jsem se od webu: https://community.home-assistant.io/t/diy-zigbee-bed-chair-occupancy-sensor/239517

Člověk se přihlasí do aplikace, kde si bude moct vybrat restauraci, na kterou bude mít chuť.
Vybere si restauraci a aplikace ho přesune na stránku, kde si bude moct vybrat stůl viz.foto STARBUCKS.jpg ve složce projektu
Potom až si vybere stůl, musí si zarezervovat stůl a budu mít 20 minut aby přišel, jinak rezervace propadá, aby si mohl rezervovat někdo jiný, či jiný člověk v restauraci aby si mohl sednout.
Aplikace je ve vývoji, ale potom by se mohlo přidat menu jídla/kávy pro zákazníky.

Aplikaci jsem vytvářel jako originalní plán, takže najít něco podobného bylo vskutku těžké a dělat to sám bylo ještě těžší.




Děkujeme, že používáte TableWatch! 🍽️
