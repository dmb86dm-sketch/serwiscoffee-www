SERWISCOFFEE – POPRAWKI TECHNICZNE SEO

Zawartość:
- index.html – poprawiona strona główna
- robots.txt – pozwala robotom indeksować stronę i wskazuje sitemap.xml
- vercel.json – przekierowuje /index.html i /index.php na adres główny

Wgraj wszystkie trzy pliki do głównego katalogu (root) repozytorium GitHub,
obok siebie. Zastąp istniejący index.html. Następnie poczekaj na wdrożenie Vercel.

UWAGA: Przekierowania adresu IP 216.198.79.1 nie da się zagwarantować samym
plikiem HTML. To adres infrastruktury hostingu; jeśli audyt nadal go zgłasza,
sprawdź w Vercel ustawienie Primary Domain i przekierowanie domeny.

Sitemap: robots.txt wskazuje https://www.serwiscoffee.pl/sitemap.xml.
Jeżeli sitemap.xml nie istnieje w repozytorium, należy go dodać osobno.
