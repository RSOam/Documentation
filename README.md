# Dokumentacija

Programska rešitev implementira portal za najem polnilnih postaj za električna vozila. <br />
Rešitev je implementirana v programskem jeziku Go, z izjemo spletnega vmesnika. Ta je implementiran z uporabo JavaScript knjižnice React. Vsaka storitev uporablja svojo MongoDB podatkovno bazo. <br />
<br />
Rešitev v osnovi uporabnikom omogoča naslednje: <br />
- Ustvarjanje in upravljanje uporabniškega računa
- Ogled in rezervacijo polnilnih naprav
- Ocenjevanje/komentiranje polnilnih naprav
- Ogled komentarjev/ocen polnilnih naprav

Rešitev je sestavljena iz petih komponente, štirih mikrostoritev in spletnega vmesnika <br />
- [Chargers service](https://github.com/RSOam/chargers-service) :  Storitev za upravljanje in ogled polnilnih postaj
- [Comments and Ratings service](https://github.com/RSOam/comments-and-ratings-service) :  Storitev za upravljanje in ogled komentarjev ter ocen
- [Reservations service](https://github.com/RSOam/reservations-service) :  Storitev za upravljanje in ogled rezervacij
- [Users service](https://github.com/RSOam/users-service) :  Storitev za upravljanje in ogled uporabnikov
- [Website](https://github.com/RSOam/web-interface) :  Spletni vmesnik za lažjo uporabo rešitve

Mikrostoritve: <br />

Chargers service : http://20.85.179.80:8080 <br />
Metode:
- GET /chargers
- GET /chargers/{id}
- POST /chargers
- PUT /chargers/{id}
- DELETE /chargers/{id}

Comments and ratings service : http://20.81.92.178:8080 <br />
Metode:
- GET /comments
- GET /comments/{id}
- GET /comments/
- POST /comments
- PUT /comments/{id}
- DELETE /comments/{id}

- GET /ratings
- GET /ratings/{id}
- GET /ratings/
- POST /ratings
- PUT /ratings/{id}
- DELETE /ratings/{id}

Reservations service : http://52.151.216.234:8080 <br />
Metode:
- GET /reservations
- GET /reservations/{id}
- GET /reservations/
- POST /reservations
- POST /reservations/closest
- PUT /reservations/{id}
- DELETE /reservations/{id}

Users service : http://20.81.116.229:8080 <br />
Metode:
- GET /users
- GET /users/{id}
- POST /users
- POST /users/login
- PUT /users/{id}
- DELETE /users/{id}
