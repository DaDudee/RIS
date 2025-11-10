# RIS – Spletna aplikacija za upravljanje receptov

RIS je preprosta **full-stack** spletna aplikacija za upravljanje kuharskih receptov.  
Uporabnik lahko dodaja, ureja, briše in pregleduje recepte preko React frontenda, ki komunicira z REST API-jem v Spring Boot backendu in uporablja podatkovno bazo MySQL.

---

## Funkcionalnosti

- prikaz seznama vseh receptov
- prikaz podrobnosti izbranega recepta (sestavine, opis, postopek)
- dodajanje novega recepta
- urejanje obstoječega recepta
- brisanje recepta
- ločen **frontend** in **backend**

---

## Tehnologije

**Backend**

- Java 17
- Spring Boot
- Spring Web, Spring Data JPA
- MySQL
- Maven

**Frontend**

- React
- React Router
- Axios
- (po želji) Bootstrap / CSS framework

---

## Struktura projekta

```text
RIS/
  backend/      # Spring Boot REST API (CRUD nad recepti)
  frontend/     # React aplikacija (SPA)
  README.md
  

  
---
## Zagon backenda

cd backend
mvn spring-boot:run

## Zagon frontenda

cd frontend
npm install
npm start
