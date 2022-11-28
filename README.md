# DesignLaboratoryEiT
16.10.2022
W pierwszym tygodniu pracy nad projektem, zapoznaliśmy się z środowiskiem programistycznym oraz nowym dla nas CircuitPythonem.
Posiłkowaliśmy się poniższym filmem w serwisie YouTube
https://www.youtube.com/watch?v=opes_7Uf49U
Korzystaliśmy również z artykułu na stronie AdaFruit, w którym mogliśmy zapoznać się z aspektami fizycznymi oraz programistycznymi platformy Clue.
https://learn.adafruit.com/adafruit-clue/circuitpython

24.10.2022
W drugim tygodniu pracy nad projektem, znaleźliśmy przykładowe kody programowania smartwatcha. W środowisku CircuitPython zaprogramowaliśmy nasze urządzenie i próbowaliśmy przeanalizować znalezione kody programów.
Przykładowe programy jakie testowaliśmy:
Kompas: https://github.com/davedice/Adafruit-CLUE-Compass
Termometr: https://learn.adafruit.com/adafruit-clue/clue-temperature-and-humidity-monitor
CLUE Spirit Level: https://learn.adafruit.com/adafruit-clue/clue-spirit-level
CLUE Height Calculator: https://learn.adafruit.com/adafruit-clue/clue-height-calculator

30.10.2022 (tydzień 3)
Pomocna okazała się być strona circuitpython.org, gdzie pod adresem https://docs.circuitpython.org/projects/clue/en/latest/api.html znaleźliśmy przykłady obsługi czujników, przycisków, touchpadów itd. Podczas pracy z biblioteką clue zauważyliśmy, że rezerwuje ona niektóre porty na własny użytek i korzystając z niej, nie można korzystać np. z biblioteki digitalio. Napisaiśmy kilka prostych programów w których możliwe jest sterowanie diodą LED oraz RGB za pomocą przycisków, touchpadów czy za pomocą gestów.

06.11.2022 (tydzień 4)
Naszym celem było zaczęcie przygody z modułem Bluetooth. Bazowaliśmy na przykładowych kodach znajdujących się w pliku z pobranymi potrzebnymi bibliotekami, o stronę https://docs.circuitpython.org/projects/ble/en/latest/api.html#, https://learn.adafruit.com/now-playing-bluetooth-apple-media-service-display/code-the-apple-media-service-display oraz https://learn.adafruit.com/introduction-to-bluetooth-low-energy/introduction.
Na podstawie tych źródeł napisaliśmy prosty program, dzięki któremu płytka Clue steruje odtwarzaczem muzyki na urządzeniu połączonym przez bluetooth. Urządzenie musi mieć system operacyjny iOS. Oczywiście nie obyło się bez problemów, które opatrzyliśmy komentarzami w kodzie. Napisliśmy również inny prosty program, który wyświetla podstawowe informacje zbierane z czujników, pozwala na kontorlowanie koloru diody RGB za pomocą ruchu oraz realizuje funkcje wygaszania ekranu.

14.11.2022 (tydzień 5)
Z powodu braku wiekszej ilości wolnego czasu, zajęliśmy się analizą i zrozumieniem (przez testowanie na własnej płytce, krok po kroku z tutorialem) jednego z projektów udostępnionych na GitHub: https://github.com/andreamah/Adafruit-CLUE-Snake-Game. Na zrozumienie kodu poświęciliśmy dłuższą chwilę, ponieważ nie wszystko co jest tam zastosowane, było nam znane.

21.11.2022(tydzień 6) W tym tygodniu skupiliśmy się głównie na poszukiwaniu możliwości graficznego interfejsu. Znaleźliśmy wiele pomocnych programów i poradników z różnych środowisk, żeby poznać całkowite możliwości płytki CLUE. Następnie staraliśmy się samodzielnie zaprogramować płytkę do wyświetlania MENU użytkownika.
Przykłady poradników oraz repozytoriów z jakich skorzystaliśmy:
- https://www.youtube.com/watch?v=ZTE-hqM6GPo&ab_channel=JamesTobin
- https://github.com/jisforjt/CircuitPython_CLUE_Menu
- http://webcache.googleusercontent.com/search?q=cache:fFBZoZMu2_oJ:www.ulisp.com/show%3F2NWA+&cd=1&hl=en&ct=clnk&gl=us
