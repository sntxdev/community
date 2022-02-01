# Выпуск технической карты SubQuery

![](https://cdn-images-1.medium.com/max/800/1*Qcu5mFIs8eJhAXaMpWOlMQ.png)

**SubQuery объявляет основные этапы, включая график TGE**

Сегодня мы рады впервые опубликовать нашу подробную техническую дорожную карту. Цель SubQuery - стать ведущим поставщиком данных в экосистеме Polkadot, и поддержка, которую мы получили от сообщества, чтобы помочь нам реализовать это видение, была потрясающей. От нашего официального основания в конце 2020 года через [Web3 Grant](https://web3.foundation/) до выпуска нашей первой версии с открытым исходным кодом в январе 2021 года и [закрытия нашей серии A в сентябре](https://subquery.medium.com/series-a-1abed6c1c2af) мы хотели бы сказать спасибо за всю вашу поддержку на протяжении этих этапов!

По мере того, как мы продолжаем набирать обороты, пришло время рассказать больше о наших планах на будущее, включая нашу техническую дорожную карту. Мы воодушевлены тем, как следующая эволюция SubQuery повысит ценность экосистемы Polkadot и предоставит нашему сообществу больше возможностей для участия в нашем росте.

## Наше будущее

Хотя SubQuery уже обслуживает миллионы запросов к данным каждый день для [более чем 60 проектов на Polkadot& Kusama](https://project.subquery.network/), мы хотим сделать так, чтобы наша следующая фаза роста была организованной и контролируемой.

По этой причине мы считаем крайне важным продемонстрировать и полностью протестировать масштабируемость сети SubQuery с помощью стимулируемой программы тестовой сети. Этот процесс также позволит нам создать сообщество индексаторов перед публичным запуском через TGE в марте 2022 года и нашу  майнет сеть в конце следующего года.

![](https://miro.medium.com/max/2400/1*I6mko5xumHAArzGePvEZiQ.jpeg)

Таким образом, ключевые результаты в нашем рабочем процессе можно разбить на следующие основные этапы.

## Где мы сейчас находимся - середина четвертого квартала 2021 года

### Поддержка EVM для парачейнов

Вскоре мы выпустим [нашу бета-поддержку для реализаций виртуальной машины Ethereum (EVM)](https://medium.com/@subquery/subquery-adds-ethereum-virtual-machine-evm-functionality-in-integration-with-moonbeam-and-ddbcdf0fd8ff) от Polkadot. Это позволяет разработчикам Polkadot и Ethereum легко интегрировать данные Substrate и EVM в одно место и запрашивать этот единственный источник данных с помощью GraphQL.

SubQuery представит более продвинутые фильтры, чем другие индексаторы, позволяя фильтровать неконтрактные транзакции, отправителей транзакций, контракты и аргументы индексированных журналов, поэтому разработчики могут создавать широкий спектр проектов, которые удовлетворяют их конкретные потребности в данных.

### SubQuery Academy

Академия предназначена для повышения квалификации и расширения возможностей разработчиков в экосистеме SubQuery, предоставляя им модульное обучение. [Наш первый курс в Академии - это _Курс героев_](https://doc.subquery.network/academy/herocourse/), он был запущен в пятницу, 22 октября 2021 года.

В каждом модуле _Курса героев_ есть несколько уроков от 5 до 10 минут, которые предоставляются в виде записанного видео. Видеоконтент сопровождается письменными руководствами, слайдами, рабочими книгами и ссылками на готовый репозиторий кода GitHub.

Курс предназначен для того, чтобы разработчик ничего не знал о SubQuery и стал экспертом в создании источника данных SubQuery для своего нового блокчейн-приложения.

В следующие несколько месяцев мы будем расширять возможности обучения для сообщества, с еженедельными выпусками нового контента SubQuery _Курс героя_ и другими курсами в ближайшие недели.

### Подтверждение индексации

Подтверждение индексации позволяет нам гарантировать, что два разных индексатора, работающих с одним и тем же проектом SubQuery, проиндексировали одни и те же данные. Это критически важный компонент, необходимый для разработки децентрализованной сети SubQuery. Мы используем концепцию под названием «Merkle Mountain ranges», чтобы подтвердить и гарантировать это, следите за будущими сообщениями в блоге, которые исследуют это глубже.

### Premium Enterprise Service

У нас есть несколько крупных клиентов, таких как Karura, Kodadot и Fearless Wallet, у которых все производственные приложения работают в SubQuery. Эти команды требуют улучшенного обслуживания и более высокого уровня надежности.

Мы справляемся с этой задачей, предлагая соглашения об уровне обслуживания, уровни корпоративных услуг и другие инструменты, которые нужны нашим крупным клиентам для ведения собственного бизнеса и получения максимальной производительности от SubQuery для своих приложений.

Пожалуйста, свяжитесь с командой, если вы хотите поговорить с нами о получении услуг корпоративного уровня и поддержки от SubQuery.

## Этап 1 — Конец 4 кв. 2021 г

### Билдеры SubQuery/ Программа грантов

Эта программа грантов предназначена для облегчения и стимулирования инноваций с помощью Polkadot и SubQuery, а также для создания следующего поколения dApps, которые приведут в действие революцию web3. Она будет поддерживать новые проекты грантами, технической поддержкой, советами по маркетингу и развитию бизнеса от SubQuery и других.

Мы очень рады возможностям этого и скоро опубликуем дополнительную информацию.

### Координатор и реализация клиентского SDK

Мы будем улучшать наш основной SDK SubQuery и добавлять дополнительные компоненты для координатора и клиента SubQuery.

Координатор индексатора будет развернут индексаторами, чтобы открыть сеть для индексатора и позволить индексатору зарегистрироваться в сети SubQuery и объявить данные, которые он делает доступными

Клиентский SDK предназначен для роли потребителя и позволит им находить индексатора и управлять всей транзакцией, которая потребуется потребителю для получения и оплаты данных.

### Внутренний MVP-контракт SQT Network

Наша первая версия сети SubQuery будет в рамках смарт-контракта, развернутого на ведущем парачейне Polkadot. Внутренний MVP позволит нам начать внутреннее тестирование всего, что здесь есть, и является для нас огромным этапом.

### EU Cluster

Наши клиенты запрашивают поддержку для большего количества кластеров для данных SubQuery по всему миру. Больше кластеров означает большую отказоустойчивость, а данные SubQuery размещаются ближе к их клиентам. Новый европейский кластер означает более быстрые запросы для потребителей, непревзойденную производительность для разработчиков dApp и большую отказоустойчивость для сети SubQuery.

### Улучшения subql init

Команда _subql init_ знакома всем, кто создал проект SubQuery; он представляет собой чистый холст - безграничные возможности. Мы понимаем, что можем лучше помочь другим начать работу. Разработчикам нужен пустой каркас, на котором уже написан весь шаблонный код.

Этот пункт дорожной карты представляет работу, которую мы хотим выполнить, чтобы позволить разработчикам начать работу над любым парачейном, не беспокоясь о конечных точках, словарях и типах - все это экономит время разработчиков и помогает другим начать работу.

## Этап 2 — Середина 1 кв. 2022 г

### Публичный запуск testnet

Следуя внутреннему MVP контракта SQT Network, мы пригласим небольшую группу участников на борт присоединиться к нам, когда мы начнем тестирование SubQuery Network. До запуска нам нужно выполнить большое количество задач и еще больший объем документации!

В начале 2022 года мы поделимся дополнительной информацией об этом процессе и о том, как вы можете подать заявку на участие.

### Моментальная индексация

Представьте себе возможность узнать состояние цепочки блоков в определенный момент времени - как именно выглядел проект SubQuery в 5-миллионном блоке? Это именно то, что предоставит эта новая функция.

### Сетевой контракт SQT v1 и внешний аудит кода

Все важные сети требуют сквозного аудита кода со стороны внешнего партнера, чтобы гарантировать безопасность и масштабируемость кода сети. SubQuery ничем не отличается, поэтому мы будем работать с ключевыми партнерами для полного аудита кода, а также продолжим делать аудит кода для наших смарт-контрактов в будущем.

### Внутреннее тестирование микроплатежей

Для нас это ключевая особенность. Мы собираемся проделать большую работу в экосистеме Polkadot для управления и обработки микроплатежей в SubQuery. Преимущество Polkadot - крошечные комиссии за транзакции по сравнению с другими сетями, такими как Ethereum, что означает, что микроплатежи гораздо более актуальны. После того, как мы проведем тщательное внутреннее тестирование, это будет внедрено в нашу сеть стимулированного тестирования.

### Сетевой обозреватель и приложение SubQuery

Мы создаем проводник и другие приложения, которые позволят участникам сети SubQuery исследовать и находить данные в сети SubQuery. Потребители также будут использовать это для навигации по библиотеке поддерживаемых источников данных, а делегаторы будут анализировать, как работают индексаторы, чтобы решить, как делегировать свои токены SQT.

### Enterprise health monitoring

Следуя нашему уровню обслуживания SubQuery Enterprise, вы также можете ожидать, что для клиентов будет доступен большой объем средств мониторинга работоспособности и других инструментов анализа производительности.

## Этап 3 — Конец 1 кв. 2022 г

### Генерация токена SQT

После успешного этапа тестирования сети мы ожидаем запустить токен SubQuery на Polkadot. В ближайшие недели мы поделимся с сообществом дополнительной информацией о нашей токеномике.

### Запуск стимулированной тестовой сети с микроплатежами

Это заключительный этап нашей тестовой сети. Мы выпустим все в нашу тестовую сеть и ожидаем, что участники доведут ее до предела. Это включает в себя масштабное и нагрузочное тестирование, точную настройку наших экономических моделей и коэффициентов, тестирование нашей документации и процессов адаптации, а также проверку того, что вы можете совершать транзакции с предшественником SQT внутри него.

Мы ожидаем, что будем вознаграждать участников нашей тестовой сети, тех, кто выполняет определенные квесты или задания.

### Аналитика и отчеты о трафике данных

Каждый день мы обрабатываем миллионы запросов данных к проектам SubQuery. У большинства наших клиентов нет аналитики в собственных децентрализованных приложениях для обеспечения конфиденциальности пользователей, но им все равно нужно знать, как работают их децентрализованные приложения, поэтому мы будем улучшать это.

### Масштабируемая интеллектуальная маршрутизация

У нас есть цель - ежедневно получать миллиард запросов SubQuery к нашей размещенной службе, поэтому мы собираемся представить глобально масштабируемую службу с несколькими запущенными службами, размещенными на сервере SubQuery.

Это новая и постоянно улучшающаяся функция, которая автоматически направляет запросы на ближайшую доступную ноду. Кроме того, это позволяет нам немедленно перенаправлять все запросы в резервную зону SubQuery, обеспечивая нам отказоустойчивую систему в случае сбоя в регионе.

В будущем это означает, что мы будем создавать все больше и больше небольших служб, размещенных в SubQuery, тактически расположенных ближе к нашим пользователям.

## Этап 4 — Середина 2 кв. 2022 г

### Запуск SubQuery Foundation

В нашем шаге по созданию децентрализованной сети SubQuery мы создадим SubQuery Foundation для контроля за будущим управлением и ростом экосистемы. Первоначально право собственности на сеть SubQuery будет передаваться в рамках основы SubQuery.

### Завершить исследование других цепочек уровня 1

Хотя нашим домом всегда будет Polkadot, мы изучаем возможность поддержки различных других блокчейнов уровня 1 с помощью наших возможностей индексирования.

### Программа добычи ликвидности

Чтобы повысить ликвидность токена SQT, мы создадим программу добычи ликвидности с децентрализованной биржей (DEX). Это позволит держателям токенов получить прибыль от своих инвестиций.

## Этап 5 — Конец 2 кв. 2022 г

### Запуск основной сети 🚀

После того, как мы завершим тестирование сети SubQuery, будет запущена первая основная сеть SubQuery Network. Здесь все действительно только начинается. Сначала мы будем подключать и награждать участников тестовой сети, а затем она будет полностью открыта для всех в сообществе.

### Запуск централизованного обмена

Чтобы стимулировать более широкое внедрение SQT, мы ожидаем, что в этот период будет запущен токен на одной, если на нескольких ведущих CEX, а также на многих других DEX.

## Этап 6— Долгосрочные планы

### Запускаем наш собственный Парачейн

Хотя изначально мы планируем сотрудничать с ведущим парачейном Polkadot для более быстрого выпуска и масштабирования SubQuery Network, в долгосрочной перспективе SubQuery также намеревается запуститься на собственном парачейне и еще больше интегрироваться в экосистему.

Этот собственный парачейн позволит нам и дальше внедрять инновации в инструменты, которые могут помочь разработчикам быстрее строить будущее Web3. Мы хотим нацелиться на слот парачейна, когда у нас будет проверенный послужной список, а также данные, сообщество и токен для его поддержки.

### SubQuery Foundation переходит в DAO

До этого еще далеко, но мы всегда мечтаем, чтобы SubQuery в конечном итоге стал DAO, принадлежащим сообществу. Мы много раз говорили, что сообщество играет огромную роль в SubQuery, все, что мы делаем, делается для наших клиентов - становление DAO является воплощением этого стремления.

При этом до этого еще далеко, и мы сделаем это только тогда, когда мы будем абсолютно уверены в успехе SubQuery и в будущем вместе с сообществом.

## Про SubQuery

[SubQuery](https://subquery.network) - это уровень децентрализованного агрегирования данных, индексации & запросов между блокчейнами уровня 1 и децентрализованными приложениями. Протокол абстрагируется от идиосинкразии данных блокчейна с помощью SubQuery SDK, позволяя разработчикам сосредоточиться на развертывании своего основного продукта, не тратя напрасно усилия на специальные серверные технологии.

​​[Linktree](https://linktr.ee/subquerynetwork) | [Website](https://subquery.network/) | [Discord](https://discord.com/invite/78zg8aBSMG) | [Telegram](https://t.me/subquerynetwork) | [Twitter](https://twitter.com/subquerynetwork) | [Matrix](https://matrix.to/#/#subquery:matrix.org) | [LinkedIn](https://www.linkedin.com/company/subquery) | [YouTube](https://www.youtube.com/channel/UCi1a6NUUjegcLHDFLr7CqLw)