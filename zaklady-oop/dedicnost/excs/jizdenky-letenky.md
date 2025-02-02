---
title: Jízdenky a letenky
demand: 4
---

Nyní je naším cílem práce pro společnost, která se zabývá prodejem jízdenek a letenek.

- Vytvoř třídu `Ticket`, která bude mít atributy `basic_price` (základní cena) a `seat_number` (číslo sededla). Tato třída bude sloužit například pro cesty autobusem.
- Při cestování vlakem musíme řešit, jestli cestující využívá 1. nebo 2. třídu. Vytvoř třídu `TrainTicket`, která bude mít navíc atribut `fare_class` (uvažujeme možnosti `economy` a `business`). Dále naprogramuj metodu `get_price()`, která bude vracet hodnotu stejnou jako `basic_price`, pokud atribut `fare_class` je `economy`, a cenu o 20 % vyšší oproti `basic_price`, pokud `fare_class` je `business`.
- U letenek řešíme třídu, kterou cestující letí, navíc ale musíme řešit i počet odbavených zavazadel. Vytvoř třídu `PlaneTicket`, která bude dědit od třídy `TrainTicket` a bude mít navíc atribut `checkout_luggages`, který udává počet odbavených zavazadel. Naprogramuj metodu `get_price()`, která bude vracet hodnotu stejnou jako `basic_price`, pokud atribut `fare_class` je `economy`, a cenu o 50 % vyšší oproti `basic_price`, pokud `fare_class` je `business`. Dále připočti 2000 za každé odbavené zavazadlo (bez ohledu na třídu).
- Vytvoř jízdenku na vlak se základní cenou 150 do tříd `economy` i `business`. Zkontroluj, jakou hodnotu vrací metoda `get_price()`.
- Vytvoř letenku se základní cenou 6000 do tříd `economy` i `business` s jedním odbaveným zavazadlem. Zkontroluj, jakou hodnotu vrací metoda `get_price()`.
