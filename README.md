<p align="center"><img src="img/helpdesk_new.svg"></p>

<div align="center">
  <h3> Руководство по работе с нашим <a href="https://testnet.joystream.org/"> текущим тестнетом</a> с которым Вы можете ознакомиться используя указанные ниже ссылки<h3>
</div>

<div align="center">
  <h4>
    <a href="/roles/validators">
      Валидаторы
    </a>
    <span> | </span>
    <a href="/roles/council-members">
      Члены Совета
    </a>
    <span> | </span>
    <a href="/roles/storage-providers">
      Поставщики Хранилищ
    </a>
    <span> | </span>
    <a href="/roles/content-curators">
     Кураторы Контента
    </a>
    <span> | </span>
    <a href="/roles/builders">
      Сборщики
    </a>
  </h4>
</div>
<div align="center">
  <h5>
    <a href="/tools/cli">
      CLI
    </a>
    <span> | </span>
    <a href="/roles/content-creators">
      Создатели Контента
    </a>
  </h5>
</div>
</br>

Оглавление
---

<!-- TOC START min:1 max:3 link:true asterisk:false update:true -->
- [Обзор](#Обзор)
  - [Вклад](#Вклад)
  - [Получение денег за участие](#получение-денег-за-участие)
- [Начало](#Начало)
  - [Генерация ключей](#генерация-ключей)
  - [Получение членства](#получение-членства)
- [Поощрения](#поощрения)
- [Программа для членов-учредителей](#программа-для-членов-учредителей)
- [Активные роли](#активные-роли)
  - [Валидаторы](#валидаторы)
    - [Описание](#описание)
    - [Стимулы](#стимулы-1)
  - [Члены Совета](#члены-совета)
    - [Описание](#описание-1)
    - [Стимулы](#стимулы-2)
  - [Поставщики Хранилищ](#поставщики-хранилищ)
    - [Описание](#описание-2)
    - [Стимулы](#стимулы-3)
  - [Кураторы Контента](#кураторы-контента)
    - [Описание](#описание-3)
    - [Стимулы](#стимулы-4)
  - [Сборщики](#сборщики)
    - [Описание](#описание-4)
    - [Стимулы](#стимулы-5)
- [Другие Функции и Инструменты](#другие-функции-и-иструменты)
  - [Создатели контента](#создатели-контента)
    - [Описание](#описание-5)
  - [CLI](#cli)
  - [Сетевой Форум](#сетевой-форум)
<!-- TOC END -->

# Обзор
Данный репозиторий содержит детальное руководство для поддержки пользователей по взаимодейтсвию с нашим текущим [тестнетом](https://testnet.joystream.org/).

## Содействие
Если вы обнаружите, что что-то не так или отсутствует в этих руководствах, пожалуйста создайте отчет о [проблеме](https://github.com/Joystream/helpdesk/issues), или лучше всего, сделайте ветку для проблемного репозитория и создайте [PR](https://github.com/Joystream/helpdesk/pulls) чтобы помочь нам стать лучше!

## Получение Денег за Участие
Токен тестовой сети Joystream (tJOY) поддерживается фиатным пулом, номинированным в долларах США, и в настоящее время погашается через Bitcoin Cash. Более подробную информацию о том как это работает Вы можете найти ниже. Если Вы хотите найти текущий курс обмена когда фиатный пул пополняется и отслеживать статус незавершенных обменов, перейдите [сюда](https://www.joystream.org/testnet).

Для обмена Ваших монет, следуйте этим шагам.
1. Чтобы мы знали, адрес для оплаты, Вы должны связать свой адрес Joystream с адресом Bitcoin Cash. Самый простой способ сделать это открыть на боковой панели вкладку `My Memo` в разделе `My Keys`. Убедитесь, что в раскрывающемся списке, в правом верхнем углу интерфейса Pioneer выбрана правильная учетная запись (именно та учётная запись которая содержит токены, которые Вы хотите обменять)

```
# Ниже в заметке размещена только часть строки:
1OR3ORqORzYOURBBITCOINCASHADDRESS
```

2. Отправьте Вашие тестовые монеты (tJOY) на следующий адрес:

```
5D5PhZQNJzcJXVBxwJxZcsutjKPqUPydrvpu6HeiBfMaeKQu
```

Как только монеты будут зачислены на этот адрес, сразу после этого, время, дата, Ваш адрес, Ваши заметки и текущий курс обмена tJOY/USD будут записаны в журнал. Затем Ваши токены сжигаются (уменьшая выпуск tJOY), и сумма в долларах вычитается из фиатного пула. Это означает, что на обменный курс это не повлияет. Ваш Bitcoin Cash должен быть доставлен в течение 72 часов, поскольку мы выполняем групировку транзакции. Также обратите внимание, что учитывается обменный курс BCH/USD на момент перевода Bitcoin Cash.

# Начнём
Чтобы начать работу и участвовать в тестовых сетях Joystream, вы должны сначала сгенерировать `Ключи`, и зарегистрироваться для получения `Членства`. Для этого не требуется никакого программного обеспечения или загрузка, так что Вы можете сделать это в вашем браузере в Pioneer [здесь](https://testnet.joystream.org).

## Генерация ключей
Нажмите `Mои Ключи` на боковой панели, затем нажмите кнопку `Добавить аккаунт`. Выбор, который Вы сделаете здесь, в определенной степени зависит от того, что Вы собираетесь делать. Если Вы просто хотите "поиграться", Вы можете следовать рекомендуемым настройкам по умолчанию. Если у Вас есть конкретная роль, тогда Вы можете перейти по ссылке на инструкции в [заголовок документа](#заголовок-документа), или ознакомиться с ними более детальней [здесь](#активные-роли).

В любом случае `Ключи` будут автоматически сохраняться в хранилище Вашего браузера для вашего удобства, но даже в этом случае безопаснее всего сохранить `seed фразу` (она Вам нужна для определенных ролей) и сохранить файл .json, который связанный с ключом. `Мнемоник` также может быть использован для восстановления ваших `ключей`,но рекомендуется хранить файл .json в безопасном месте, поскольку это предпочтительный формат, используемый для импорта Вашего ключа в определенные инструменты, такие как [CLI](/tools/cli).

## Получение членства
Стать `участником` платформы, Вам понадобятся токены. `Кран` в настоящий момент закрыт из-за "Sybil" атак хотя мы работаем над фрикционным краном, который надеемся выпустить в ближайшее время. В настоящее время единственный способ получить токены - это присоединиться к нашему [Discord server](https://discord.gg/DE9UN3YpRP) и получить их там. Эта группа также является отличным местом, чтобы получить поддержку и обсудить Joystream с другими членами сообщества.

**Примечание:**
В настоящее время комиссия отсутствует для большинства транзакций, однако частично Pioneer по-прежнему будет требовать от Вас положительный баланс, не менее 1-го tJOY, чтобы Вы могли выполнять определенные действия.

Нажмите `Членство` на боковой панели, и выберите вкладку `Регистрация`. Выберите `Обработка/Псевдоним`. При желании укажите ссылку на файл изображения для вашего аватара, и заполните поле `About`.

# Поощрения
Тестовые сети Joystream стимулируются, это означает, что пользователи могут зарабатывать реальные деньги за участие. Мы выбрали такую систему по многим причинам, но одним из основных факторов является создание сообщества, которое понимает работу сети. После того, как платформа будет запущена в основной сети, Jsgenesis не будет управлять критически важной инфраструктурой, занимать роли, необходимые для работы платформы, или стимулировать инновации.

В предыдущих сетях выплачивались еженедельные выплаты для всех ролей, причем размер вознаграждений и доступных позиций определялся Jsgenesis. Старая схема стимулирования работала следующим образом, она привлекла небольшую группу пользователей к участию и зарабатыванию Bitcoin Cash за выполненый вклад в развитие. В данном случае тестнет токены (tJOYs) использовались для достижения нужного результата. Пользователям нужна была всего лишь небольшая сумма для стейкинга ролей, и получения вознаграждения в виде Bitcoin Cash, без учёта tJOY в качестве ценного актива.

Когда Joystream запустит майнет, где никто не заплатит Bitcoin Cash вознаграждения, поэтому платформа будет использовать только токены JOY как на единицу ценности для поддержания критически важной инфраструктуры для продолжение развития, управления, а также для стимулирования создателей контента. Для того чтобы получить структуру которая наилучшим образом отражает стимулы основной сети, мы решили, что выпуск токенов tJOY будет поддерживаться фиатным пулом, где пользователи могут конвертировать свои токены, чтобы покрыть свои реальные затраты, время и оборудование. Основы новой схемы изложены ниже:  

-   При запуске новой сети выдача токенов будет перенесена из предыдущей сети, а существующий фиатный пул будет «перенесен» в новую сеть.
-   На каждый период консульства (на текущий момент 2 недели), сумма в долларах США будет добавлена в фиатный пул в качестве периодического пополнения, таким образом это увеличивает ценность каждого токена, если предположить, что выпуск остается постоянным.
-   Однако, все роли на платформе будут компенсированы новыми токенами tJOY, эффективно увеличивая предложение.
-   Помимо периодического пополнения, набор ключевых показателей эффективности Совета также настраивается нами, чтобы сеть работала должным образом.
-   Если KPI будет достигнут, пул фиатных денег будет увеличиваться на сумму, рассчитанную на основе успеха уровня для каждого KPI, новые tJOY токены будут майнится пропорционально, и они будут переданы `Членам Совета` и избирателям, которые их избрали. Как следствие, это не повлияет на стоимость держателей токенов, не участвующих в управлении.
-   Другие способы увеличения предложения tJOY и фиатного пула включают в себя вознаграждения, конкурсы, предложения по расходам и т.д.

Можно найти обзор того, как работает новая схема стимулирования и как она взаимодействует с новой моделью предложения, которая дает пользователям гораздо больше полномочий и ответственности через совет [здесь](/tokenomics).

# Founding Member Program

Alongside the testnet incentive structure associated with earning tJOY (redeemable for BCH) from participation, we are also rewarding high-quality project contributors with allocations of mainnet JOY tokens through our new Founding Member Program.

We have launched this program to ensure that a sufficiently large, effective and motivated community of users is ready to occupy all the different roles required to run, evolve and grow the platform on mainnet.

You can read more about the program in the [dedicated GitHub repo](https://github.com/joystream/founding-members), or on our [website](https://www.joystream.org/founding-members/).

# Active Roles

The list below shows the currently active roles available at our current [testnet](https://testnet.joystream.org/). In order to know how to best allocate your tokens, you can experiment with the [tokenomics spreadsheet](https://docs.google.com/spreadsheets/d/13Bf7VQ7-W4CEdTQ5LQQWWC7ef3qDU4qRKbnsYtgibGU/edit?usp=sharing).

## Validators

<p align="center"><img src="img/validators.svg" width="500"></p>

### Description
In proof of stake systems, block producers, or `Validators`, are typically paid a fixed amount for each block produced. `Validators` must run a full node.

A detailed guide to setting up the `Validator` node and settings can be found [here](/roles/validators).

### Incentives

Active `Validators` are rewarded in tJOY every new `era` (600 blocks). The size of the reward for each `Validator` depends on a couple of variables:

- The number of `Validators`
  - The total amount awarded is independent of the number of active `Validators`. This means that the individual tJOY reward is the total reward divided by the number of `Validators` in the last `era`.
- The total supply of tJOY
  - The rewards for `Validators` are calculated as a percentage of the total tJOY issuance.
- The ratio of tokens at stake for the `Validator` set compared to the total token issuance on the network
  - By summing up the stake of the individual `Validators` and their `Nominators`, you get the total amount at stake.
  - Divide by the tJOY issuance and you get the ratio.
  - The ideal number (for the `Validators`) is 25%.
  - If this number is higher or lower, than 25%, the rewards "drop off"

The rewards for the last `era` will show up as an event, and can be seen in the [explorer](https://testnet.joystream.org/#/explorer), if you keep a window open. Fairly precise estimates can be found on the [Tokenomics page](https://testnet.joystream.org/#/tokenomics) in Pioneer, or (in most cases) by looking at the "last reward" in [here](https://testnet.joystream.org/#/staking/targets).
If you want to exchange your tokens, you need to unbond them first. Check the guide for instructions on how to do this.

A change to note introduced in the Alexandria testnet is the fact that payouts to validators are no longer paid automatically.
However, you have two weeks to claim your rewards, so, for example, if you forget for 15 days, you'll only "lose" a day of earnings.
(Also, anyone can claim for anyone, so a nominator will not suffer if the associated validator forgets)

## Council Members

<p align="center"><img src="img/councilmembers.svg" width="500"></p>

### Description

`Council Members` are elected by the stakeholders in the system to act in the long-term interest of the platform. The `Council` is responsible for allocating resources, and hiring executive personnel to run the platform's day-to-day operations.

An overview of the proposal system can be found [here](/proposals).
A detailed explanation of the election cycle and responsibilities can be found [here](/roles/council-members).

### Incentives

`Council Members` receive recurring rewards in tJOY. Unlike the other recurring rewards for roles, this is not something the `Council` can vote on, as it could lead to some unfortunate outcomes. The size of the reward can be found can be found in the chain state.

Council Members also receive [Council KPI rewards](/tokenomics/README.md#council-kpis) on top of the recurring rewards.

## Storage Providers

<p align="center"><img src="img/storageproviders.svg" width="500"></p>

### Description

You can't have a video platform without videos, so someone has to take the role of storing the data. In the future, this will be a highly specialized role, focusing on what is implied by the name of the role. Currently, it will in practice also entail the future `Bandwidth Provider` role.

Unlike `Validators` that can come and go without too much friction (at least for now), a new `Storage Provider` will currently need to replicate the entire content directory. As a consequence, the platform needs some stability for this role to avoid providing a poor user experience, or worse, loss of data.

After an upgrade of the `Constantinople` network, the `Storage Provider` role will now be within its own working group, with a lead overseeing the day-to-day operations, while being accountable to the Council.

A detailed guide on being a Storage Provider and the associated responsibilities can be found [here](/roles/storage-providers).

### Incentives

The `Storage Lead` can only be hired (or fired) by the Council through the proposal system. The Lead should maintain sufficient storage and distribution capacity by employing `Storage Providers`, and paying them sufficiently. The Lead will also need to run a storage node themselves. Another important task is to keep an eye on the working group's financing (deciding how much each `Storage Provider` should be paid etc.).

The current status of this role can be found [here](https://testnet.joystream.org/#/working-groups).

## Content Curators

<p align="center"><img src="img/contentcurators.svg" width="500"></p>

### Description

`Content Curators` will one day be essential for ensuring that the petabytes of media items uploaded to Joystream are formatted correctly and comprehensively monitored and moderated. Our upcoming testnet allows this content monitoring to take place by giving users who are selected for the role administrative access to the Joystream content directory to make changes where necessary.

A detailed guide on being a Content Curator and the associated responsibilities can be found [here](/roles/content-curators).

### Incentives

`Content Curators` are hired by the `Curator Lead`. The `Council` is responsible for setting the budget for the `Curators` by providing the lead with a so called mint. The lead can hire and fire as they choose, but if the capacity of the mint runs out, the rewards will stop flowing. This means that both the `Council` and the lead must pay attention to the mint capacity.

The group and its lead is governed through the proposal system, where any member can propose to "Set Content Working Group Mint Capacity", and "Set (Curator) Lead".

The former, if executed, will simply set the capacity of the mint to the number proposed, regardless of previous capacity. To avoid workers "striking" due to the lack of payments (including for themselves), the lead must ensure the mint does not run out of capacity. If the lead goes rogue, or simply spends too much, the capacity can be set to zero to avoid further spending.

When making a new "Set (Curator) Lead" proposal, one can propose to
- replace the old lead
- hire a lead if there are currently none
- fire the current lead, without setting a new one.


## Builders

<p align="center""><img src="img/bugreporters.svg" width="500"></p>

### Description
Unlike the other roles, `Builders` are not a formal role, with automatic on-chain rewards. Instead, Jsgenesis will create "Bounties", with specified tasks, conditions and rewards.

The tasks associated with these Bounties will ideally try to solve some problem either for the community or Jsgenesis, but in some cases, their main purpose will be to create some fun and/or attract new members to the community. In some cases, Bounties may be created as a result of requests from the Council or the community.

Over time, the tasks should allow people with different skillsets and interests to participate. Most challenges will be easier if you are somewhat technical or creative, but in other situations it will simply require putting in some time and effort. To learn more about Bounties, go to the `Builders` section [here](/roles/builders).

### Incentives

The incentives will be to claim all, or parts, of the reward associated with the Bounty.

# Other Features and Tools

This section covers other things you can do after [getting started](#get-started), that aren't paid roles at the moment.

## Content Creators

<p align="center"><img src="img/contentcreators.svg" width="500"></p>

### Description

When the Joystream mainnet is live, `Content Creators` will be responsible for creating and uploading the enormous variety of different content types and genres which we believe will allow Joystream to grow into a successful decentralized media platform.

## CLI
The CLI tool is under development, but is already needed for the [Storage Lead](/roles/storage-lead), [Curators and Lead](/roles/content-curators), [Content Creators](/roles/content-curators), and can be useful for [Storage Providers](/roles/storage-providers). Go [here](/tools/cli) for more information and guides.

## On-Chain Forum

This is the first step in providing users, infrastructure role participants, `Council Members` and future stakeholders a way to communicate and coordinate. Hopefully, this method of interaction will further help in developing a strong community around Joystream. Note that you have to be a `member` to post, and only the forum moderator (forum sudo) can create categories.
