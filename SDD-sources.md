# Источники по внедрению Spec-Driven Development

Подборка официальных материалов Microsoft/GitHub, AWS и Google. Ссылки проверены 14 сентября 2026 года.

Здесь собраны руководства и примеры применения SDD. Публикация на сайте компании сама по себе не означает внедрение подхода во всей компании. Приведённые результаты проектов — заявления авторов, а не независимые сравнительные исследования.

## 1. GitHub — введение и рабочий процесс Spec Kit

[Spec-driven development with AI: Get started with a new open source toolkit](https://github.blog/ai-and-ml/generative-ai/spec-driven-development-with-ai-get-started-with-a-new-open-source-toolkit/)

Дата: 2 сентября 2025 года.

Объясняет внедрение через Spec Kit: Specify → Plan → Tasks → Implement, с проверкой результатов каждого этапа. На этапе Specify фиксируются пользовательские сценарии, цель и критерии успеха; технические решения появляются на этапе Plan.

Полезно для разделения формирования intent, технического планирования и реализации. Команды приведены в контексте версии инструмента на дату публикации.

## 2. Microsoft — командный процесс и практические примеры

[Spec-Driven Development: A Spec-First Approach to AI-Native Engineering](https://developer.microsoft.com/blog/spec-driven-development-ai-native-engineering/)

Дата: 10 июня 2026 года.

Описывает распределение работы между продуктом, архитекторами, разработчиками и тестированием. В примере существующего проекта, по словам автора, подключение новых типов объектов сократили с 2–3 недель до нескольких дней благодаря переиспользуемым спецификациям.

Полезно для обсуждения внедрения SDD в команде и выбора необходимой глубины процесса: не каждое изменение требует полного цикла.

## 3. AWS — конкретный пример разработки с Kiro

[From spec to production: a three-week drug discovery agent using Kiro](https://aws.amazon.com/blogs/industries/from-spec-to-production-a-three-week-drug-discovery-agent-using-kiro/)

Дата: 18 февраля 2026 года.

Команда AWS описывает создание приложения тремя специалистами за три недели: сбор требований, проектирование, спецификации, реализация и проверка. Показано использование requirements.md, design.md, tasks.md и общих инструкций проекта.

Полезно как конкретный пример применения SDD с описанием этапов и сроков. Срок и готовность решения заявлены авторами кейса.

## 4. Google — практическая лабораторная работа

[Spec-Driven ADK Agent Development with Antigravity and Spec-kit](https://codelabs.developers.google.com/sdd-adk-antigravity)

Пошаговое применение SDD: изучение репозитория, подготовка контекста, спецификация, уточнение, план, задачи и реализация. Артефакты сохраняются в Git.

Полезно для построения процесса из skills, контекста проекта и отдельных этапов. Это учебное руководство, а не отчёт о внедрении SDD внутри Google.

## 5. AWS — применение в legacy-проекте

[From Mainframes to Microservices: Specification-Driven Mainframe Modernization with AI Agents](https://aws.amazon.com/blogs/migration-and-modernization/from-mainframes-to-microservices-specification-driven-mainframe-modernization-with-ai-agents/)

Дата: 19 августа 2026 года.

Разбирает получение бизнес-правил из существующего кода, преобразование их в спецификации и последующую реализацию с проверкой. Используются AWS Transform и Kiro.

Полезно для понимания того, как начать SDD в системе с большим объёмом существующего кода и неполной документацией.

## 6. AWS — контроль работы AI-агентов

[Balancing speed and safety: A control framework for AI coding agents](https://aws.amazon.com/blogs/security/balancing-speed-and-safety-a-control-framework-for-ai-coding-agents/)

Дата: 30 июля 2026 года.

Рассматривает SDD как часть процесса с проверками между этапами, ограничениями инструментов и автоматическими проверками. Описывает управление агентом во время разработки и проверку результата в сборочном процессе.

Полезно при проектировании ограничений для агента: текстовые инструкции дополняются контролем инструментов и процесса. Материал шире темы SDD.

## С чего начать

- №1 — разделение intent, планирования и реализации.
- №4 — практическое устройство процесса и skills.
- №3 — конкретный опыт применения.
- №2 — внедрение в командный процесс.
- №5 — работа с legacy.
- №6 — управление действиями агентов и проверки.
