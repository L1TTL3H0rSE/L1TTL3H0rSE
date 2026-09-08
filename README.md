# Николай

**Frontend-разработчик · Vue / Nuxt / TypeScript**

Разрабатываю веб-интерфейсы для образования, совместной работы и игр: видеоконференции, личные кабинеты, интерактивные расписания. В собственных проектах работаю и с серверной частью на Go — от API и хранения данных до синхронизации клиентов.

[Email](mailto:shelovek002@gmail.com) · Москва

### Проекты, с которых стоит начать

#### [WikiPulse — карта правок Википедии и аналитика](https://github.com/yt-wikipulse/wikipulse)

**React · TypeScript · Vite · Яндекс Карты · H3**

Командный проект: карта географически привязанных правок Википедии и дашборд исторической аналитики. Данные проходят через YTsaurus / SPYT и REST API к браузерному приложению.

Мой вклад — развитие React-фронтенда, обработка сетевых ошибок и состояний интерфейса, исправления геометрии карты и поведения карточек правок. Также работал над CI и подготовкой проекта к открытой публикации.

[Открыть демо](https://wiki-pulse.ru) · [Архитектура frontend](https://github.com/yt-wikipulse/wikipulse/blob/main/docs/architecture/frontend.md) · [Обновление данных карты](https://github.com/yt-wikipulse/wikipulse/blob/main/frontend/src/features/live-map/useLiveMapData.ts) · [Мои коммиты](https://github.com/yt-wikipulse/wikipulse/commits/main/?author=L1TTL3H0rSE)

Демостенд воспроизводит снимок реальных правок за 30 августа 2026 года.

#### [Munchkin — многопользовательская карточная игра](https://github.com/L1TTL3H0rSE/munchkin)

**Nuxt · Vue · TypeScript · Go · PostgreSQL · SSE**

Комнаты, пошаговая игра и отдельное представление состояния для каждого игрока. Сервер проверяет действия и скрывает чужие карты; клиент получает события об изменении версии и запрашивает актуальные данные. В репозитории есть игровой движок с детерминированным replay, тесты и интерфейсы для разных размеров экрана. Проект развивается.

[Синхронизация клиента](https://github.com/L1TTL3H0rSE/munchkin/blob/main/frontend/applications/web/app/composables/game/realtime.ts) · [Игровой интерфейс](https://github.com/L1TTL3H0rSE/munchkin/tree/main/frontend/applications/web/app/components/game) · [Тесты frontend](https://github.com/L1TTL3H0rSE/munchkin/tree/main/frontend/applications/web/test)

#### [Template monorepo — основа для веб-приложений](https://github.com/L1TTL3H0rSE/template-monorepo)

**Nuxt · Vue · Pinia · Storybook · Go · PostgreSQL**

Референсный проект с отдельными пакетами компонентов, состояния и API. В примере приложения — поиск, пагинация и оптимистичные обновления; устаревший ответ запроса не может перезаписать новые данные. Архитектурные решения описаны рядом с кодом.

[Компоненты и Storybook](https://github.com/L1TTL3H0rSE/template-monorepo/tree/master/frontend/packages/components/src/components) · [Управление состоянием](https://github.com/L1TTL3H0rSE/template-monorepo/blob/master/frontend/applications/web/app/stores/characters.ts) · [Архитектура](https://github.com/L1TTL3H0rSE/template-monorepo/blob/master/docs/ARCHITECTURE.md)

#### [Route planner — маршрут по дорожному графу](https://github.com/L1TTL3H0rSE/digital-partners-global)

**Nuxt · TypeScript · Pinia · Leaflet · GeoJSON**

Тестовое задание: интерактивная карта с выбором и перетаскиванием точек. Дорожная сеть преобразуется в граф; маршрут рассчитывается собственной реализацией алгоритма Дейкстры. Направления движения и односторонние дороги не учитываются.

[Построение графа и поиск пути](https://github.com/L1TTL3H0rSE/digital-partners-global/blob/master/stores/maps.ts)

<details>
<summary><strong>Ещё проекты: расписание, мобильная видеосвязь и эксперименты с дизайном</strong></summary>

- [RSU Timetable](https://github.com/L1TTL3H0rSE/RSU-Timetable) — интерфейс университетского расписания на Nuxt / Vue, работа с Directus API, фильтрами и календарной сеткой.
- [VKS Mobile](https://github.com/L1TTL3H0rSE/vks-mobile) — мобильный клиент видеоконференций на React Native / Expo и LiveKit: комнаты, участники, чат и управление аудио и видео.
- [LeinoDesign](https://github.com/L1TTL3H0rSE/leinodesign) — экспериментальный навык для работы с редактируемыми компонентами в Figma; в репозитории сохранены задания и результаты сравнительных проверок.

</details>

### Сейчас: leinoctl

Разрабатываю CLI-инструмент для управления изменениями в репозиториях при работе с AI-агентами. Он связывает согласованный план, разрешённые файлы и проверки; запускает работу в отдельном Git worktree и проверяет результат перед интеграцией.

**Node.js · JavaScript · SQLite · Git · CLI / MCP**

### Технологии

**Основной frontend:** Vue 3, Nuxt, TypeScript, JavaScript, Pinia, HTML, CSS / SCSS, Storybook, Vite.

**Интеграции:** REST API, Keycloak, Directus, LiveKit / WebRTC, WebSocket, SSE.

**В собственных проектах:** Go, PostgreSQL, Node.js, React Native / Expo, Docker, CI/CD.

Мне интересны задачи, где нужно разобраться в предметной области, продумать поведение интерфейса и довести его до работающего сценария.
