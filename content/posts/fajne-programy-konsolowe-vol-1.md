---
title: "Fajne programy konsolowe vol. 1"
date: 2023-07-20T23:25:29+02:00
draft: false
ShowToc: true
TocOpen: true
tags: ["terminal"]
categories: ["Programy terminalowe"]
---
### Trochę okienek (GNU Midnight Commander)

Kupiłeś sobie VPSa, więc masz kompa do którego możesz dostać się z każdego miejsca na świecie z dostępem do internetu?
No i super.

Wreszcie logujesz się do swojego VPSa... Twoim oczom ukazuje się przepiękny interfejs użytkownika...
![Piękny widok :)](ssh.png)

Ogarnijmy to trochę. Przydałaby się jakaś namiastka okienek, co? Ręka świerzbi, żeby użyć myszki...
Z pomocą przychodzi [**GNU Midnight Commander**](https://midnight-commander.org/).

Twoja dystrybucja na pewno go dostarcza. Zakładając, że jesteś Ubuntowy, zrobisz tak:

    $ sudo apt install mc
    $ mc

I już po chwili Twoim oczom ukaże się coś trochę ładniejszego:
![Trochę lepiej, co?](mc1.png)

(P.S. Ta belka na dole jest klikalna, ale pokazuje też funkcje przypisane do klawiszy F1 - F12)

#### Zmiana wyglądu

Co więcej, możesz sobie używać myszki ;) Interfejs przywodzi na myśl jakieś stare DOSowe menedżery plików, albo Total Commandera. Proponuję zacząć od zmiany skórki na coś mniej rozpieszczającego oczy xd
![Wszystko możesz wyklikać](mc2.png)
![To chyba moja ulubiona skórka](mc3.png)

#### Podglądanie zawartości plików

Tęsknisz za możliwością podglądu zawartości plików? Zerknij, co możesz ustawić dla paneli.
![Ustawianie podglądu pliku](mc4.png)
![No i tego da się używać](mc5.png)

Ta funkcja na pewno pomaga w szybkim zlokalizowaniu odpowiedniego skryptu, albo po prostu w szybszym przeglądaniu zawartości serwera. Da się też podglądać obrazki, ale wszystko w swoim czasie ;)

Jeśli chcesz przesyłać pliki z/do innej maszyny, albo po prostu przeglądać jej zawartość, wystarczy że masz dostęp do niej przez ssh.

#### Łączenie po powłoce

![Łączenie po powłoce](mc5.5.png)
W następnym oknie podajesz hasło do ssh i...
![Widok innej maszyny](mc6.png)
Enjoy graficzny dostęp do innego serwera :) Osobiście często na domowym komputerze korzystam z tej formy łączenia z VPSem.

Szybka edycja plików tekstowych ulubionym edytorem jest dostępna pod F4.

GNU Midnight Commander to wg mnie must have.