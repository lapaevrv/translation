---
layout: mechanics
title: Правила LeSS (April 2017)
order: 8
---
<small>([что изменилось по сравнению с предыдущей версией](/less/rules/rules-changes.html))</small>
Правила LeSS определяют каркас LeSS. Это то, что обязательно к выполнению. Почему? Ответ вы можете узнать здесь [Почему LeSS?](../framework/why-less.html) section.
{: .no_printing}

## Правила LeSS

LeSS применяется к продуктам, над которыми работают от 2-8 команд.

### Организационная структра в LeSS

* Структурируйте организацию, используя реальные команды, как минимальный строительный блок организации.
* Каждая команда – это самоуправляемая, кросс-функциональная, колоцированная, и долгоживущая структурная единица.
* Основная масса команд – это клиентоориентированные продук-ориентированные команды (feature-team).
* Скрам Мастера отвечают за хорошо работающее внедрение LeSS в организации. Их основной фокус составляют команды, Владелец Продукта, организация и практики разработки. Скрам Мастер не фокусируется только на одной команде, а его фокус составляет вся организационная система компании.
* Скрам-Мастер – это выделенная на 100% занятость роль.
* Один Скрам Мастер может обслуживать от 1 до 3 команд.
* В LeSS роль менеджеров опциональна, но если они все-таки присутствуют, то их роль меняется. Их фокус смещается с управления ежедневными активностями на улучшение способностей поставки ценности всей системы продуктовой разработки компании.
* Роль менеджмента – это улучшение продуктовой разработки компании за счет практики подхода Go See, и продвижения подхода Stop & Fix, а также «экспериментирование важнее соответствия».
* Установите полностью LeSS структуру в продуктовом подразделении компании с самого начала – это критически важно для внедрения LeSS.
* Для остальной части организации за пределами продуктового подразделения внедряйте LeSS эволюционно, используя подход Go See, для создания организации, в которой экспериментирование и улучшение – это норма.

### Продукт в LeSS

* Для всего поставляемого продукта есть только один Владелец Продукта и один Продуктовый Бэклог
* Владелец Продукта не должен работать один над Уточнением Продуктового Бэклога; он поддерживается множеством команд, которые работают непосредственно с заказчиками/пользователями и другими заинтересованными лицами.
* Вся приоритезация происходит через Владельца продукта, но прояснение как можно более напрямую с командами, заказчиками/пользователями и другими заинтересованными лицами.
* Определение продукта с одной стороны должно быть широким и ориентированным на конечного пользователя/заказчика, а с другой стороны практичным в текущих условиях.
* С течением времени определение продукта может расширяться. Более широкое определение продукта предпочтительнее.
* Один Definition of Done для всего продукта и общий для всех команд.
* Каждая команда может иметь свой Definition of Done, расширяющий и более строгий, чем общий DoD.
* Цель совершенства – это совершенствование DoD до такой степени, что итогом станет возможность отгружать продукт каждый спринт или даже чаще.

### Спринт в LeSS
{: .always_page_break_before}

* Существует один общий продуктовый спринт для всех команд, а не отдельные спринты для каждой из команд. Каждая из команд начинает и заканчивает спринт в один и тот же момент. Результатом каждого спринта является целиком интегрированный продукт.
* Планирование спринта состоит из двух частей. Первая Часть Планирования Спринта является общей для всех команд, в то время как Вторая Часть Планирования Спринта обычно осуществляется каждой из команд по отдельности. В случае связанных элементов бэклога проводите Межкомандную Вторую Часть Планирования Спринта в общем рабочем пространстве.
* На Первой Части Планирования Спринта присутствуют Владелец Продукта и Команды, либо представители команд. Они ориентировочно выбирают те элементы бэклога, над которыми будет работать каждая из команд. Команды проясняют существующие вопросы и возможности совместной работы.
* У каждой команды свой Бэклог Спринта.
* На Второй Части Планирования Спринта каждая из команд в отдельности решает каким образом они реализуют выбранные элементы бэклога. Обычно это приводит к созданию их Бэклога Спринта.
* Каждая из команд проводит свой Ежедневный Скрам.
* Кросскомандная координация организуется самими командами. Предпочтительнее децентрализованная и неформальная координация вместо централизованной координации. Обращайте внимание на следующие практики: Just Talk (Просто Обсудите) и неформальные сети с помощью коммуникации через код, межкомандные встречи, менторы компонентов, путешественники, скауты и опен-спейсы.
* Уточнение Бэклога осуществляется каждой командой по тем элементам бэклога, которые они вероятнее всего будут делать в будущем. Проводите межкомандное и всекомандное уточнение бэклога для усиления общего понимания и обнаружения необходимости в координации в случаях связанных элементов бэклога, либо при необходимости получения более широкой обратной связи от команд или в целях обучения.
* Есть только одно Ревью Спринта и оно общее для всех команд. Убедитесь в том, что на Ревью Спринта присутствуют все заинтересованные лица, которые могут предоставить информацию необходимую для эффективной инспекции и адаптации
* Каждая команда проводит свою Ретроспективу Спринта.
* Общая Ретроспектива проводится после того, как проведены ретроспективы команд, для обсуждения кросскомандных и системных проблем, и для разработки экспериментов по совершенствованию системы. Эта ретроспектива проводится при участии Владельца Продукта, Скрам Мастеров, Представителей Команд и менеджеров (если таковые есть).

## Правила LeSS Huge
{: .always_page_break_before}

LeSS Huge подходит для продуктов, над которыми работает 8 и более команд. Избегайте использования LeSS Huge для продуктовых групп меньшего размера, так как это приведет к большим накладным расходам и локальным оптимизациям.

В LeSS Huge используются все правила LeSS, если иное явно не указано. В каждой Области Требований используется обычный каркас LeSS.

### Организационная структура в LeSS Huge

* В Область Требований группируются клиентские требования, которые сильно связаны с клиенсткой точки зрения.
* Каждая команда специализируется только в одной Области требований. Команды работают над одной Областью Требований в долгосрочной перспективе. Команды могут переключиться на другую Область Требований, когда наступает момент, в который ценность в другой Области Требований значительно превышает ценность текущей Области Требований.
* За каждую Область Требований отвечает один Владелец Области Продукта.
* В каждую Область Требований входит от 4 до 8 команд. Избегайте нарушения этого ограничения.
* Внедрение LeSS Huge, включая структурные изменения, производятся, используя эволюционный инкрементальный подход.
* Помните: Внедрение LeSS Huge требует месяцев и даже лет кропотливой работы, бесконечного терпения и чувства юмора.

### Продукт в LeSS Huge

* За каждую Область Требований отвечает один Владелец Области Продукта.
* Один Владелец Продукта отвечает за приоритезацию с точки зрения продукта целиком и принимает решение, какая команда занимается какой Областью Требований. 
* Владелец продукта работает в тесном контакте с Владельцами Областей Продукта.
* Владельцы Областей Продукта выполняют роль Владельца Продукта для своих команд.
* Существует только один Бэклог Продукта; каждый элемент бэклога продукта относится только к одной Области Требований.
* Для каждой области продукта существует один и только один Бэклог Области Продукта. Бэклог Области Продукта – это более детальное представление соотвествующих элементов Бэклога Продукта.

### Спринт в LeSS Huge

* Существует только один общий спринт уровня всего Продукта, а не отдельные спринты для каждой Области Требований. Спринт завершается интеграцией всего продукта.
* Владелец Продукта и Владельцы Областей Продукта синхронизируются на постоянной основе. До Планирования Спринта они убеждаются, что команды работают над самыми ценными элементами Бэклога Продукта. После Обзора Спринта они также обеспечивают адаптацию на уровне продукта.

Переведено при поддержке [ScrumTrek](http://scrumtrek.ru/)