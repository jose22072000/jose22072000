# Jose Manuel Sánchez

Informatics Engineer and full-stack developer. I spend most of my time on backend and
systems that actually run in production — GPS route tracking, order management and delivery
logistics for a distribution company — and on the Flutter apps and Next.js panels on top of
them.

Available for remote work (Contractor), LATAM / international time zones.

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

Also work with React, Vue, Django and Laravel.

## Selected work

**[procovar-rutas](https://github.com/jose22072000/procovar-rutas)** · Go · Next.js · PostgreSQL · Redis
GPS route tracking for field salespeople. Ingests the daily `.gpx` logs from 53 Google Drive
folders (~1,800 files) into Postgres, then serves a layered Leaflet map where route, stops
and the day's clients toggle on and off separately. Cross-references each route against the
orders for that day ("visited 6 of 8 clients" — 30 km means nothing if they were driving in
circles). Built to handle the real files: one day is 49,565 GPS points. Timezone-correct end
to end (TIMESTAMPTZ + `America/Havana`), so DST weeks don't shift the reports.

**[delivery-logistica](https://github.com/jose22072000/delivery-logistica)** · Go · Flutter
Offline-first delivery app for 10 branch logistics operators. They have connection in the
morning and none during the day, so the app has to live on the device — code, session and
data. A Go API (35 routes, 11 models), a sync service (delta download, batch upload, device
registry), and a single Flutter codebase that compiles to both web and Android.

**[PEDIDO](https://github.com/jose22072000/PEDIDO)** · TypeScript
Order management system for the branches — the source the routing and delivery services read
their orders and client geolocation from.

**[linux-hardware-center](https://github.com/jose22072000/linux-hardware-center)** · Python · GTK4
Hardware control panel for Linux laptops: temperatures, draggable fan curves, self-switching
power profiles, battery care and hybrid-GPU switching. Detects the hardware instead of
assuming it.

## Contact

Email · josework2207@gmail.com
