---
title: "Pierwszy VPS i pierwsze kroki"
date: 2023-07-21T18:53:46+02:00
draft: true
ShowToc: true
TocOpen: true
tags: ["VPS", "Mikrus", "serwer"]
categories: ["Tutoriale"]
---
### Co to jest VPS?

VPS - *Virtual Private Server* - to twój kawałek serwerowego tortu :)
W przeciwieństwie do *serwera dedykowanego*, czyli maszyny którą masz całą dla siebie,
kupując VPSa dostajesz serwer wirtualny. Z niewielkimi wyjątkami\* **w pełni funkcjonalny serwer** hostowany
u Twojego hostingodawcy.

### Mikrus

Ten wpis może i jest kryptoreklamą Mikrusa, ale bardzo polecam tę usługę.
Po pierwsze: kosztuje tyle co kilka kebabów **rocznie**
Po drugie: jego support jest state-of-art, zarówno adminów jak i społeczności

#### Proces kupowania VPSa w Mikrusie

Wchodzisz [tutaj](https://mikr.us) i wybierasz najtańszą opcję. Mikrus 1.0 z niecałymi 400MB RAMu, jednym rdzeniem, 5GB dysku, bez wirtualizacji. Bez obaw, będziesz mógł zrobić upgrade do wyższej opcji.

![Pierwszy krok](pakiety.png)

Potem czytasz **dokładnie** regulamin. Płacisz w dogodny dla siebie sposób i czekasz na maila z danymi do logowania :)

![Drugi krok](regulamin-i-dodatki.png)

![Panel admina z widocznymi opcjami: Amfetamina, MARIAN, otwórz Ticketa](panel-admina.png)

Okej. Otrzymałeś dane do logowania i Twoim oczom ukazuje się panel admina. Polecam zapoznać się z jego możliwościami.
1. M.A.R.I.A.N. - odpalasz go, kiedy masz wielkie problemy z serwerem - na przykład nie odpowiada, kiedy próbujesz się z nim połączyć przez ssh.
2. Amfetamina - to zastrzyk dodatkowych zasobów dla Twojego serwera na 30 minut za free, kiedy musisz np. go zaktualizować (przy 400MB RAMu może być z tym różnie :P)
3. Tajemniczy przycisk na górze "Otwórz ticketa" to nic innego, jak kontakt do administratorów Mikrusa. **Kontaktujesz się z nimi tylko po puszczeniu M.A.R.I.A.N. -a na twoim serwerze**.



###### Przypisy
\* - *na przykładzie Mikrusa, w najniższym pakiecie nie uruchomisz Dockera. Nie zaktualizujesz również jądra. VPSy posiadają swoje pewne ograniczenia, które nie wejdą nam w drogę w większości zastosowań.*