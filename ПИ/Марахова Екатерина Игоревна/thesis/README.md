## Разработка адаптивного веб-приложения для восстановления мелкой моторики рук у пациентов в период реабилитации

**Ключевые слова:** мелкая моторика, реабилитация, веб-приложение, компьютерное зрение, MediaPipe, микросервисная архитектура, распознавание жестов, JWT-аутентификация, контейнеризация, Docker, React, телемедицина, реабилитационные упражнения

### Аннотация

Выпускная квалификационная работа посвящена созданию адаптивного веб-приложения для восстановления мелкой моторики рук пациентов в период реабилитации. В отличие от дорогостоящих аппаратных решений, разработанное программное обеспечение функционирует с использованием лишь обычной веб-камеры и браузера, что делает реабилитационный процесс доступным в домашних условиях. Система реализована в виде набора микросервисов и использует библиотеку MediaPipe для распознавания жестов в реальном времени без серверной обработки видеопотока.
Результаты работы включают:
- реализацию микросервисной архитектуры с выделенными сервисами аутентификации, упражнений и пользовательского интерфейса;
- разработку алгоритма бинарной классификации жестов на основе данных о положении пальцев;
- построение адаптивного интерфейса на React с визуальной обратной связью и режимами сложности;
- внедрение безопасной авторизации пользователей с помощью JWT и REST API;
- контейнеризацию приложения и настройку развёртывания с использованием Docker и docker-compose;
- создание сценариев упражнений с параметризованной настройкой и возможностью расширения набора жестов.
Предложенное решение сочетает доступность, масштабируемость и технологическую гибкость, позволяя использовать его как в клиниках, так и для самостоятельной реабилитации пациентов. Работа демонстрирует возможности интеграции современных web-технологий и компьютерного зрения в медицину, открывая перспективы для дальнейших исследований в области цифровой реабилитации и телемедицины.

------
## Development of an adaptive web application for rehabilitation of fine hand motor skills in rehabilitation patients

**Keywords:** fine motor skills, rehabilitation, web application, computer vision, MediaPipe, microservice architecture, gesture recognition, JWT authentication, containerization, Docker, React, telemedicine, rehabilitation exercises

### Abstract

This thesis presents the development of an adaptive web application designed to support fine motor rehabilitation in patients recovering from stroke, injury, or neurological conditions. Unlike traditional hardware-based systems, the proposed solution leverages only a standard webcam and browser, making the rehabilitation process more accessible for home use. The system adopts a microservice architecture and integrates MediaPipe to perform real-time hand gesture recognition entirely on the client side.
The achieved results include:
- implementation of a modular architecture with separate services for authentication, exercise handling, and UI rendering;
- development of a gesture classification algorithm based on binary encoding of finger positions;
- design of an interactive React-based interface with visual feedback and customizable exercise modes;
- integration of secure user authentication using JWT and RESTful API endpoints;
- full containerization using Docker and automated orchestration via docker-compose;
- creation of configurable exercise routines with scalable complexity and extendable gesture libraries.

The proposed solution combines accessibility, scalability, and technological robustness, making it suitable for use in clinical environments as well as at home. The project illustrates the potential of integrating modern web and computer vision technologies into medical rehabilitation and provides a foundation for further research in digital health and telemedicine.

