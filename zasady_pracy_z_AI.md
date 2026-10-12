# Zasady pracy z AI

1. Rozmowa z modelem powinna przebiegać na zasadzie rozmowy z współpracownikiem, powinna być naturalna, zwięzła i swobodna

2. Napisanie skutecznego prompta powinno składać się z 3 etapów:
    * Jakie są cele oraz jaka jest rola, dodanie kontekstu by "wtajemniczyć" model.
    * Jakie działania mają zostać podjęte, czy np. tekst ma być przeredagowany, czy coś ma zostać przeanalizowane itp.
    * Czy ma zostać narzucony styl lub ton wypowiedzi, ewentualne dołączenie przykładów na których ma wzorować się model udzielając odpowiedzi.

3. Podejście Iteracyjne
    Pierwszy prompt rzadko przynosi oczekiwany i wyczerpujący rezultat więc należy go traktować wyłącznie jako punkt startowy. Ważne jest precyzyjne punktowanie tego co powinno zostać wykonane inaczej a nie korzystanie z krótkich poleceń w stylu "skróć". Jeśli czat po rozwinięciu i dalszych promptach zszedł w złym kierunku lepszą opcją jest rozpoczęcie nowego czatu z bardziej zrozumiałym i wyczerpującym promptem początkowym.

4. W Claude można pracować z modelem na 3 sposoby:
    * Praca krok po kroku polegająca na konwersacji (użytkownik zadaje prompta, model odpowiada) co sprawdza się przykładowo przy chcęci zrozumienia działania jakiegoś mechanizmu.
    * Powierzenie zadania Claudeowi polega na wyszczególnieniu w prompcie dokładnego wyniku a model zwraca gotowy, przygotowany wynik
    * Claude Code działa w bazie kodu sprawdzając jego poprawność, testuje go i pomaga go dokumentować

5. Struktura 4D
    Jest to sposób działania z AI w 4 krokach (Delegation, Description, Discernment i Diligence)
    * Delegation - Wyznaczenie jakie zadania powinno wykonać się samemu, jakie ze sztuczną inteligencją a które pozostawić całkowicie AI
    * Description - Polega na komunikacji ze sztuczną inteligencją w sposób prowadzący do produktywnej współpracy i oczekiwanych wyników
    * Discernment - Umiejętność oceny na ile treść generowana przez model jest poprawna, jak odpowiedź jest wytwarzana i jak zachowuje się AI
    * Diligence - Polega na wzięciu odpowiedzialności za to co wygenerowało AI, szczerość i transparentność co do używania AI w projekcie

