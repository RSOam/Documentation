# Documentation

Programska rešitev implementira portal za najem polnilnih postaj za električna vozila. <br />
Rešitev je implementirana v programskem jeziku Go, z izjemo spletnega vmesnika. Ta je implementiran z uporabo JavaScript knjižnice React. <br />
V osnovi uporabnikom omogoča naslednje: <br />
- Ustvarjanje in upravljanje uporabniškega računa
- Ogled in rezervacijo polnilnih naprav
- Ocenjevanje/komentiranje polnilnih naprav
- Ogled komentarjev/ocen polnilnih naprav

Rešitev je sestavljena iz petih komponente, štirih mikrostoritev in spletnega vmesnika <br />
- [Chargers service](https://github.com/RSOam/chargers-service) :  Storitev za upravljanje in ogled polnilnih postaj
- [Comments and Ratings service](https://github.com/RSOam/comments-and-ratings-service) :  Storitev za upravljanje in ogled komentarjev ter ocen
- [Reservations service](https://github.com/RSOam/reservations-service) :  Storitev za upravljanje in ogled rezervacij
- [Users](https://github.com/RSOam/users-service) :  Storitev za upravljanje in ogled uporabnikov
- [Website](https://github.com/RSOam/web-interface) :  Spletni vmesnik za lažjo uporabo rešitve
