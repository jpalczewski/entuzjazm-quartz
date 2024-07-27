---
title: Czy AI zastąpi programistów
draft: false
tags:
  - Typ/Insight
  - IT/godot
  - claude
  - AI
  - ChatGPT
aliases:
  - Czy AI zastąpi programistów
date: 2024-07-03
---
Na skutek jednego projektu stwierdziłem, że chcę podłubać sobie w #IT/godot  przy innym [[Tunnelify|pobocznym projekcie]], a że żyjemy w XXI wieku - niech to będzie dłubanie wspomagane sztuczną inteligencją, a dokładnie - #claude [^1].

Wygenerujmy sobie kod obsługi klikania myszki:

![[Pasted image 20240703174224.png]]
Jest ładnie, jest `match`, wygląda elegancko... Z tym tylko że nie działa: po dłuższym debugowaniu wyszło, że żadnej z opcji nie jest łapana[^2].

Działa natomiast rzemieślnicze, wyklikane przez człowieka `is`:

![[Pasted image 20240703174620.png]]

Zapytacie dlaczego? Myślę że to kwestia alternatywnego do pewnego stopnia języka, z którymi LLMy jeszcze miały za mało styczności.

Wracając natomiast do odpowiedzi z początku - na chwilę obecną jeszcze nie, ale przy dość dużym debugowaniu i uważności mogą być ciekawym wsparciem.

## Czy #ChatGPT jest lepszy?

Próbując uzyskać fajny algorytm prędkości walczę do darmowych limitów tu i tam. Chat dla odmiany jest dość oporny z umiejętnością cofania:
![[Pasted image 20240703195616.png]]


I gdy chcesz żeby wspiął się na wyżyny swoich możliwości:
![[Pasted image 20240703195655.png]]
To owszem, wspina się, ale na wyżyny halucynacji:

![[Pasted image 20240703195730.png]]



[^1]: Odpowiada mi najbardziej - czy to charakter odpowiedzi, ich styl i podatność na sugestie.
[^2]: Wszystko ląduje w domyślnej gałęzi `"_":` 