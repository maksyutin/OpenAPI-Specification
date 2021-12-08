# OpenAPI Спецификация (Русская редакция)

![Build Status](https://github.com/OAI/OpenAPI-Specification/workflows/validate-markdown/badge.svg) [![Issue triagers](https://www.codetriage.com/oai/openapi-specification/badges/users.svg)](https://www.codetriage.com/oai/openapi-specification)

![](https://avatars3.githubusercontent.com/u/16343502?v=3&s=200)


Спецификация OpenAPI - это открытая спецификация, поддерживаемая сообществом в рамках [Инициативы OpenAPI](https://www.openapis.org/), совместный проект с Linux Foundation.

Относительно назначения, OpenAPI рассматривается как универсальный интерфейс для пользователей (клиентов) по взаимодействию с сервисами (серверами). Аналогичен описаниям интерфейса для программирования более низкого уровня. Если спроектирована спецификация для некоторого сервиса, то на её основании можно генерировать исходный код для библиотек клиентских приложений, текстовую документацию для пользователей, варианты тестирования и др. Для этих действий имеется большой набор инструментов для различных языков программирования и платформ. 

OpenAPI представляет собой формализованную спецификацию и полноценный фреймворк для описания, создания, использования и визуализации веб-сервисов REST. Задачей является позволить клиентским системам и документации синхронизировать свои обновления с изменениями на сервере. Это достигается тем, что методы, параметры, модели и другие элементы посредством OpenAPI интегрируются с программным обеспечением сервера и всё время с ним синхронизируются

Документы OpenAPI описывают сервис API и представлены в форматах YAML или JSON. Эти документы могут либо создаваться и обслуживаться статически (FirstAPI), либо создаваться динамически из приложения (CodeFirst).

Спецификация OpenAPI не требует перезаписи существующих API. Это не требует привязки какого–либо программного обеспечения к сервису - описываемый сервис может даже не принадлежать создателю его описания. Однако требует, чтобы возможности сервиса были описаны в структуре спецификации OpenAPI. Не все службы могут быть описаны с помощью OpenAPI – эта спецификация не предназначена для охвата всех возможных вариантов API HTTP, но включает поддержку [API REST](https://en.wikipedia.org/wiki/Representational_state_transfer). Спецификация OpenAPI не предписывает конкретный процесс разработки, такой как сначала описание (First-API, Design-First) или сначала код (Code-First).

Этот GitHub проект может является отправной точкой для OpenAPI. Здесь вы найдете необходимую информацию об спецификации OpenAPI, простые примеры того, как она выглядит, и некоторую общую информацию о проекте, на русском языке.

## Текущая версия - 3.1.0

Текущая версия OpenAPI спецификации [OpenAPI Specification 3.1.0](versions/3.1.0.md).

### Предыдущая версия

Этот репозиторий так же содержит все [предыдущие версии](versions).

Each folder in this repository, such as [examples](examples) and [schemas](schemas), should contain folders pertaining to the current and previous versions of the specification.

## See It in Action

If you just want to see it work, check out the [list of current examples](examples).

## Инструменты и библиотеки

Looking to see how you can create your own OpenAPI definition, present it, or otherwise use it? Check out the growing
[list of implementations](IMPLEMENTATIONS.md).

## Участие

The current process for development of the OpenAPI Specification is described in 
[Development Guidelines](DEVELOPMENT.md).
Development of the next version of the OpenAPI Specification is guided by the [Technical Steering Committee (TSC)](https://www.openapis.org/participate/how-to-contribute/governance#TDC). This group of committers bring their API expertise, incorporate feedback from the community, and expand the group of committers as appropriate. All development activity on the future specification will be performed as features and merged into this branch. Upon release of the future specification, this branch will be merged to `main`.

The TSC holds weekly web conferences to review open pull requests and discuss open issues related to the evolving OpenAPI Specification. Participation in weekly calls and scheduled working sessions is open to the community. You can view the [TSC calendar online](https://openapi.groups.io/g/tsc/calendar). Look for the "Subscribe to Calendar" button for instructions on subscribing.

The OpenAPI Initiative encourages participation from individuals and companies alike. If you want to participate in the evolution of the OpenAPI Specification, consider taking the following actions:

* Review the [current specification](versions/3.1.0.md). The human-readable markdown file _is the source of truth_ for the specification.
* Review the [development](DEVELOPMENT.md) process so you understand how the spec is evolving.
* Check the [issues](https://github.com/OAI/OpenAPI-Specification/issues) and [pull requests](https://github.com/OAI/OpenAPI-Specification/pulls) to see if someone has already documented your idea or feedback on the specification. You can follow an existing conversation by subscribing to the existing issue or PR.
* Subscribe to an open issue a day (or a week) in your inbox via [CodeTriage.com](https://www.codetriage.com/oai/openapi-specification).
* Create an issue to describe a new concern. If possible, propose a solution.

Not all feedback can be accommodated and there may be solid arguments for or against a change being appropriate for the specification.

## Лицензия

Смотрите: [License (Apache-2.0)](https://github.com/OAI/OpenAPI-Specification/blob/main/LICENSE)

![Analytics](https://ga-beacon.appspot.com/UA-831873-42/readme.md?pixel)
