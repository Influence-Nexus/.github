## Influence Nexus

### Описание проекта

Influence Nexus - это симулятор влияния и стратегии, представленный в виде взвешенных направленных графов. Игрок может выбирать между различными мирами, представленными в виде когнитивных карт. Узлы графа представляют собой факторы, а дуги олицетворяют казуальные связи между этими факторами.

### Особенности игры

- **Платформа:** Web
- **Архитектура:** Клиент-сервер (REST API)

### Дизайн и пользовательский интерфейс

- UI отрисовывается в [Figma](https://www.figma.com/file/ZjJwm0d5X5uS9kV8HZh160/Influence-Nexus?type=design&node-id=0%3A1&mode=design&t=eSE7bneBzGW1azo1-1)
- Важная информация и схемы отражаются в [Miro](https://miro.com/welcomeonboard/SnJicWRnY0ZSRTYzVUZMY1NWNHMzazRpUFFyaHN1aFFzNVJpd3NOTWZYM3pYS3BGMDh0aWRtekJ2VXVrVUlYR3wzNDU4NzY0NTcxODQzNjc1OTIxfDI=?share_link_id=134297790583)

### Команда


### Задачи на GitHub

Основные задачи отражены в проекте [Influence Nexus](https://github.com/orgs/Influence-Nexus/projects/1). [MT] - основные задачи, [ST] - задачи, которые можно решить онлайн в чате.

### Архитектура проекта
![Архитектура проекта](media/архитектура%20проекта.drawio.png)

## Формат хранения данных о моделях
Для хранения моделей используется реляционная СУБД PostgreSQL. Обобщенную схему таблиц можно увидеть на рисунке:
![DB](media/UML_IN.drawio.png)

## Стек технологий:
- **ЯП**:
    - ![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
        - ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
        - ![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
    - ![JS](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
        - ![ReactJS](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
        - Vis.js.
- **БД**:
    - ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
- **Окружение**:
    - ![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white
)
# Основные ссылки
- [Теория игры](knowledge-base/gameplay/README.md)
- [Серверная часть](https://github.com/Influence-Nexus/server)
- [Front-end часть](https://github.com/Influence-Nexus/frontend)
- [Cognition](https://github.com/Simon1093/cognition/)