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
  - [Генерация ключей](#Генерация ключей)
  - [Получение членства](#Получение членства)
- [Поощрения](#Поощрения)
- [Программа для членов-учредителей](#Программа для членов-учредителей)
- [Активные роли](#Активные роли)
  - [Валидаторы](#Валидаторы)
    - [Описание](#Описание)
    - [Стимулы](#Стимулы-1)
  - [Члены Совета](#Члены Совета)
    - [Описание](#description-1)
    - [Стимулы](#incentives-2)
  - [Поставщики Хранилищ](#storage-providers)
    - [Описание](#description-2)
    - [Стимулы](#incentives-3)
  - [Кураторы Контента](#content-curators)
    - [Описание](#description-3)
    - [Стимулы](#incentives-4)
  - [Сборщики](#builders)
    - [Описание](#description-4)
    - [Стимулы](#incentives-5)
- [Другие Функции и Инструменты](#other-features-and-tools)
  - [Создатели контента](#content-creators)
    - [Описание](#description-5)
  - [CLI](#cli)
  - [Сетевой Форум](#on-chain-forum)
<!-- TOC END -->

# Обзор
Данный репозиторий содержит детальное руководство для поддержки пользователей по взаимодейтсвию с нашим текущим [тестнетом](https://testnet.joystream.org/).

## Содействие
Если вы обнаружите, что что-то не так или отсутствует в этих руководствах, пожалуйста создайте отчет о [проблеме](https://github.com/Joystream/helpdesk/issues), или лучше всего, сделайте ветку для проблемного репозитория и создайте [PR](https://github.com/Joystream/helpdesk/pulls) чтобы помочь нам стать лучше!

## Получение денег за участие
Токен тестовой сети Joystream (tJOY) поддерживается фиатным пулом, номинированным в долларах США, и в настоящее время погашается через Bitcoin Cash. Более подробную информацию о том как это работает Вы можете найти ниже. Если Вы хотите найти текущий курс обмена когда фиатный пул пополняется и отслеживать статус незавершенных обменов, перейдите [сюда](https://www.joystream.org/testnet).

Для обмена Ваших монет, следуйте этим шагам.
1. Чтобы мы знали, адрес для оплаты, Вы должны связать свой адрес Joystream с адресом Bitcoin Cash. Самый простой способ сделать это открыть на боковой панели вкладку `My Memo` в разделе `My Keys`. Убедитесь, что в раскрывающемся списке, в правом верхнем углу интерфейса Pioneer выбрана правильная учетная запись (именно та учётная запись которая содержит токены, которые Вы хотите обменять)

```
# Ниже в заметке помещается только часть строки:
1OR3ORqORzYOURBBITCOINCASHADDRESS
```

2. Отправьте Вашие тестнет монеты (tJOY) на следующий адрес:

```
5D5PhZQNJzcJXVBxwJxZcsutjKPqUPydrvpu6HeiBfMaeKQu
```

Как только монеты будут зачислены на этот адрес, сразу после этого, время, дата, Ваш адрес, ваши заметки и текущий курс обмена tJOY/USD будут записаны в журнал. Затем ваши токены сжигаются (уменьшая выпуск tJOY), и сумма в долларах вычитается из фиатного пула. Это означает, что на обменный курс это не повлияет. Ваш Bitcoin Cash должен быть доставлен в течение 72 часов, поскольку мы группируем транзакции. Также обратите внимание, что учитывается обменный курс BCH/USD на момент перевода Bitcoin Cash.

# Get Started
To get started and participate on the Joystream testnets, you must first generate `Key(s)`, and sign up for a `Membership`. This requires no software or downloads, and can be done in your browser on Pioneer [here](https://testnet.joystream.org).

## Generate Keys
Click `My Keys` in the sidebar, and then click the `Add account` button. The choices you make from here depend to a certain degree on how you intend to participate. If you just want to play around, you can follow the recommended defaults. If you have a specific role in mind, you may instead want to follow the links to the instructions in the [header of this document](#guides-to-get-started-on-our-current-testnet-in-links-below), or compare them in more detail [here](#active-roles).

In any event, the `Keys` will be automatically stored in your browser storage for your convenience, but even so it's safest to save your `Raw seed` (you need it for certain roles) and save the .json file associated with the key. The `Mnemonic` can also be used to restore your `Keys`, but keeping the .json file somewhere safe is recommended, as it is the preferred format used to import your key in to certain tools, such as the [CLI](/tools/cli).

## Get a Membership
To become a `Member` of the platform, you will need some tokens. The `faucet` is closed at the moment due to abuse from Sybil attackers though we are working on a frictional faucet which we hope to release soon. Currently, the only way to get tokens is to join our [Discord server](https://discord.gg/DE9UN3YpRP) and ask for some there. This group is also a great place to get support and discuss Joystream with other community members.

**Note:**
There are currently no fees associated with most transactions, but some parts of Pioneer will still require you to maintain a balance of at least 1 tJOY to allow you to perform certain actions.

Now, click `Membership` in the sidebar, and select the `Register` tab. Choose a `Handle/nickname`. Optionally, provide a link to an image file for your avatar, and fill in the markdown-enabled `About` field.


# Incentives
The Joystream testnets are incentivized, meaning users can earn real money for participating. There are many reasons we have chosen a system like this, but one of the main motivations is to build a community that understands the network. After the platform goes live on mainnet, Jsgenesis will not be around to run critical infrastructure, occupy the roles needed for the platform to work, or drive innovation.

Previous testnets had weekly payouts for all roles, with the magnitude of rewards and positions available decided by Jsgenesis. The old incentive scheme has worked in the sense that it has gotten a small group of users to participate and earn Bitcoin Cash for their contributions. However, the testnet tokens (tJOYs) have only been a means to an end. Users only needed a small amount to stake for roles, and get the recurring Bitcoin Cash reward, without having to consider tJOY as a valuable asset in its own right.

When Joystream goes live on mainnet, there will be no one there to pay these (Bitcoin Cash) rewards, and the platform must rely on JOY tokens as the single value carrier for maintaining critical infrastructure, continued development, governance, and to provide incentives for content creators. In order to get a structure that reflects the mainnet incentives in a better way, we have decided to have the tJOY token issuance be backed by a fiat pool, where users can convert their tokens to cover their real costs, time and hardware. The basics of the new scheme is outlined below:

-   At launch of a new network, the token issuance will be migrated from the previous network, and the existing fiat pool will be "transferred" to the new network.
-   For each Council Term (currently 2 weeks), an amount of USD will be added to fiat pool as recurring replenishment, thus increasing the value of each token, if one were to assume the issuance stays constant.
-   However, all roles on the platform will be compensated by newly minted tJOY tokens, effectively inflating the supply.
-   In addition to the recurring replenishment, a set of Council KPIs (Key Performance Indicators), will be set by us, to ensure the network is working as intended.
-   If a KPI is reached, the fiat pool will increase by the amount computed based on the level success for each KPI, new tJOY will be minted proportionally, and these will be distributed to both the `Council Members` and the voters that elected them. As a consequence, this will not affect the value of token holders not participating in the governance.
-   Other ways that the tJOY supply and the fiat pool can increase include through bounties, competitions, spending proposals, etc.

An overview on how the new incentive scheme works, and how it interacts with the new proposal model that gives far more power and responsibility to users via the council, can be found [here](/tokenomics).

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
