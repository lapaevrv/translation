---
layout: mechanics 
title: Системное мышление
order: 40
---

<div class="chapter_quote"><p>
Я прошел курс скорочтения и прочитал роман "Война и Мир" за 20 минут. Он про Россию.
<br/>
—Вуди Аллен
</p></div>


“Что бы мы ни делали, количество дефектов в нашем бэклоге всегда примерно постоянно”, говорил наш менеджер; это был наш проект, состоящий из 15 миллионов строк кода, над которым работало несколько сотен разработчиков. Как так получается? Нам может помочь разобраться системное мышление. В небольших группах правила игры неформальны и их легко понять, но при разработке крупного проекта --- или любой крупной системы --- это тяжело. Джеральд Вайнберг в этой ситуации выделяет два решающих фактора:

> **Закон Вайнберга-Брукса**{: style="color: #1997C0"}: От действий менеджеров, основанных на **неправильных моделях системы**, пострадало больше проектов, чем от всех остальных причин вместе взятых.
>
> **Ловушка причинно-следственной связи**{: style="color: #1997C0"}: У каждого результата есть причина... и мы всегда можем разобраться, что есть причина, а что - следствие. [[Weinberg92]](http://www.amazon.com/Quality-Software-Management-Systems-Thinking/dp/0932633226/ref=sr_1_1?ie=UTF8&qid=1413527418&sr=8-1&keywords=Quality+Software+Management%3A+Systems+Thinking)

Это - результат применения нашей **ментальной модели** к системе, о чем речь пойдет ниже в этой секции.

Проблемы, возникающие из-за ментальных моделей и предположений - это половина дела. Вторая проблема - что внедрение Скрама в больших масштабах, бережливое мышление и принципы гибкой разработки не ограничиваются только отделом разработки. Нам приходится сталкиваться с управлением продуктами, бюджетированием, бета-тестированием, выпуском, руководством и политиками найма. Следовательно, в случае масштабной трансформации полезно уметь собираться с коллегами и **эффективно рассуждать** о ментальных моделях, причинных связях, циклах обратной связи и механизмах управления (или иллюзии управления) большой системы, которую мы всерьёз собираемся *изменить*. Системное мышление - один из таких инструментов рассуждения.

В 1958 году журнал *Harvard Business Review* опубликовал [“Industrial Dynamics: A Major Breakthrough for Decision Makers,”](http://www.lottepiil.dk/kandidat/Industrial%20Dynamics%20(Forrester%201958).pdf) прорывную статью Джея Форрестера (Jay Forrester), профессора MIT Sloan School. Эта статья дала толчок движению системного мышления в образовании, и Школа Менеджмента MIT Sloan вскоре получила известность благодаря обучению людей **системной динамике**. Системную динамику часто воспринимают как синоним **системного мышления**, хотя последнее - более общий термин.

MIT привлек и других исследователей, ориентированных на динамику систем, таких как Питер Сендж (Peter Senge).<sup>[1](#footnote-1)</sup>

В соответствии с *законом Вайнберга-Брукса*, исследование Форрестера показало, что когда людям, принимающим решения, предлагали улучшить производительность системы на основании динамической модели бизнес системы, они *обычно делали её еще хуже* [[SKRRS94]](http://www.amazon.com/The-Fifth-Discipline-Fieldbook-Organization/dp/0385472560/ref=sr_1_fkmr0_3?ie=UTF8&qid=1413528034&sr=8-3-fkmr0&keywords=The+Fifth+Discipline+%EF%BF%BCFieldbook). Исследование показало, что большинство людей слабо способны фундаментально улучшать системы, обычно применяя неуместный "здравый смысл" и скороспелые 'решения', которые не приводят к долгосрочным систематическим улучшениям.

Почему же так сложно компетентно понять и управлять поведением большой группы разработки (или системы)? Ответ лежит, в частности, в поведении стохастических систем с очередями и изменчивостью, как показывает принцип [Теории Массового Обслуживания](./queueing_theory.html) LeSS. И тот же самый ответ лежит в *теории управления* : Большинство интересующих нас систем -- таких как группа разработки продукта -- имеют сложные позитивные и негативные циклы обратной связи и нелинейное поведение. Поведение таких систем не поддается нашей интуиции. А еще есть небольшая проблема, связанная с *людьми*.

Подводя итог, причины, по котором большие системы не поддаются пониманию и управлению, включают (но не ограничиваются):

* недостаток знаний о динамике систем, циклах обратной связи, нелинейном поведении систем и неочевидных последствиях систем на рабочем месте
* непонимание корневых причин проблем (и способов их нахождения)
  * *причин* а не единственной причины; в системном мышлении видно, что у проблемы существует несколько непрямых и динамических причин
* непонимание как и почему скороспелые решения или решения на уровне локального отдела со временем ухудшают общую производительность поставки.
<br>
<br>

Короче говоря, неспособность мыслить системно.<sup>[2](#footnote-2)</sup> 

Эти причины являются очень вескими на пересечении менеджмента и адаптации гибких и бережливых принципов в большой организации. Команда лидеров - это часть системы, подверженной изменениям; и если они не применяют системное мышление, они могут *реально* вывести систему из равновесия, в плохом смысле!

В качестве сводки инсайтов системного мышления, нам нравится [11 ‘законов’](https://en.wikipedia.org/wiki/The_Fifth_Discipline#The_11_Laws_of_the_Fifth_Discipline), описанных в книге [The Fifth Discipline](http://www.amazon.com/Fifth-Discipline-Practice-Learning-Organization-ebook/dp/B000SEIFKK/ref=sr_1_1?ie=UTF8&qid=1413531002&sr=8-1&keywords=the+fifth+discipline) ([перевод на русский язык](https://www.ozon.ru/context/detail/id/950887/)):

* Сегодняшние проблемы – результаты вчерашних 'решений'.
* Сила действия равна силе противодействия.
* Перед долговременным ухудшением наступает легкое улучшение.
* Обычно легкий выход – это путь назад.
* Бывает, что лекарство горше болезни.
* Тише едешь – дальше будешь.
* Причины и следствия разнесены во времени и пространстве.
* Результаты малых изменений бывают очень значительными, но трудно найти подходящий объект для воздействия.
* Иметь пирог и есть его – не одно и то же.
* Разделив слона пополам, не получишь двух слонят.
* Винить некого.
{: .two_columns .box_top_bottom}


Внутренняя мантра Тойоты - [“Хорошее **мышление**, хорошие продукты.”](http://www.toyota-global.com/company/toyota_traditions/quality/may_jun_2005.html) Системное мышление - это набор инструментов *мышления*, помогающих...

* **увидеть системную динамику**{: style="color: #1997C0"} --- организация, занимающаяся разработкой - это система из людей и политик с неявными циклами обратной связи и непреднамеренными последствиями
  * мы можем научиться видеть и, следовательно, улучшать систему при помощи **диаграмм причинного цикла** (casual loop diagrams, CLD), созданных во время совместной работы
* **видеть ментальные модели**{: style="color: #1997C0"} --- одна из причин неоптимальных решений - это ложные предположения и ошибочные выводы
  * это обнаруживается при составлении диаграмм причинного цикла и метода "Пять Почему"
* **увидеть локальную оптимизацию**{: style="color: #1997C0"} --- еще один источник неоптимальных решений - *локальная оптимизация*, когда принимается 'лучшее' с точки зрения отдельного человека или отдела решение, вместо **глобальной оптимизации**, исходящей из принципа бережливого производства цели *приносить пользу быстро, с высоким качеством и сильным боевым духом*.
<br>
<br>

Это введение построено вокруг следующих областей системного мышления: Учимся видеть (1) *системную динамику* , (2) *ментальные модели* , (3) *корневые причины*, и (4) *локальную оптимизацию* .

## Видеть Системную Динамику : Введение

### Статическая Сложность против Динамической Сложности

Многие из нас, особенно инженеры и финансисты, хорошо научились справляться со **статической сложностью** --- такой как анализ и управление информацией (требования, финансовый анализ, ...), декомпозировать сложные структуры на более простые, и так далее. То есть со сложностью статической, информационной или структурной природы.

Почему большие программные проекты имею тенденцию деградировать, тратя все больше и больше времени на дефекты? Что может случиться, если США вторгнется в Ирак? Чтобы увидеть динамику за этими вопросами, приходится использовать анализ **динамической сложности**.

В отличие от привычного образования, хорошо справляющимся со статическим анализом, многие из нас не получили *формального* образования по анализу *динамической* сложности<sup>[3](#footnote-3)</sup>, особенно динамики рабочей среды. Возможно, причина этого в том, что мы думаем, что в рабочей среде достаточно полагаться на здравый смысл. Форрестер продемонстрировал, что в сложных системах обычного "здравого смысла" недостаточно, и показал, что для того, чтобы лучше понимать системную динамику рабочей среды, можно обучить людей формальным методам, используя *динамические модели систем*, представленные в виде *диаграммах потока* [[Forrester61]](http://www.amazon.com/Industrial-Dynamics-Jay-Wright-Forrester/dp/1614275335/ref=sr_1_1?ie=UTF8&qid=1413582840&sr=8-1&keywords=Industrial+Dynamics).

Диаграммы потока заключают в себе материальные, финансовые и информационные потоки, метрики (переменные, имеющие количественные значения, такие как сумма денег или количество дефектов), последствия принятых решений или политик, и причинно-следственные связи. Популярное упрощение - это **диаграмма причинного цикла**, которая фокусируется на причинно-следственных связях и циклах обратной связи системы [[Sterman00]](http://www.amazon.com/Business-Dynamics-Systems-Thinking-Modeling/dp/0071179895). Есть несколько похожих нотаций; во всех присутствуют метрики (переменные), причинные связи и отложенный эффект. В книге [[Weinberg92]](http://www.amazon.com/Quality-Software-Management-Systems-Thinking/dp/0932633226/ref=sr_1_1?ie=UTF8&qid=1413527418&sr=8-1&keywords=Quality+Software+Management%3A+Systems+Thinking) это называется *диаграммой воздействия*.

### Первый закон построения диаграмм: Моделируйте, чтобы обсуждать

Чтобы научиться видеть системную динамику используйте диаграммы причинно-следственных связей, в идеале, нарисованные на доске в рамках всеобщей ретроспективы LeSS с коллегами. Но прежде, чем двигаться дальше, давайте поговорим про *Первый закон построения диаграмм*

> **Основная ценность диаграмм заключается в обсуждениях в процессе их построения---мы моделируем, чтобы обсуждать.**

Когда группа собирается вместе, чтобы нарисовать на доске диаграмму причинно-следственных связей (Обсуждения и размышления - это самое важное в процессе построения диаграмм, Valtech India.), основная ценность заключается в обсуждениях и общем знании, которое появляется в процессе построения модели. Представление этого знания в виде наглядной диаграммы также важно для создания (на доске) конкретных и однозначных идей --- ментальных моделей, которыми обладают люди --- потому что слова сами по себе могут быть нечёткими и непонятными. Тем не менее, диаграмма вторична по отношению к тому, что люди унесут с собой - знания и пересмотренное понимание в результате обсуждения.


<figure>
  <img class="rounded shadowed" src="/img/systems_thinking/group%20cld%20modeling.jpg" alt="group%20cld%20modeling.jpg">
  <figcaption>Системное мышление. Совместная разработка диаграммы причинно-следственных связей —-- моделирование ради обсуждения.</figcaption>
</figure>


*Конкретный совет для построения диаграмм* : Мы начинаем, записывая на стикерах *переменные*. Стикер может содержать запись "Скорость разработки фич" или “Количество дефектов”. Мы размещаем стикеры на доске. Затем мы рисуем причинно-следственные связи между стикерами. В процессе построения диаграммы всегда приходится много переписывать, стирать, перерисовывать. Самый важный результат - это *понимание*; в дополнение, кто-то из участников захочет сфотографировать то, что получилось на доске.

## Видеть системную динамику: Диаграммы причинно-следственных связей

Диаграммы причинно-следственных связей часто используются при знакомстве с LeSS, чтобы увидеть системную динамику того, что происходит при разработке больших систем. Уже только ради этой цели имеет смысл их понять. Ещё полезнее нарисовать на доске несколько схем вместе с коллегами. Моделируйте ради обсуждения. Когда? Например, во время всеобщей ретроспективы LeSS.

Практическая ценность этого совета более важна, чем может показаться на первый взгляд. Очень расплывчато и малорезультативно "быть системномыслящим". Но если вы и четверо ваших коллег возьмёте за привычку вставать вместе у большой доски и рисовать диаграмму причинно-следственных связей, это уже конкретная и потенциально высокорезультативная практика, которая связывает "*быть* системномыслящим" и "*мыслить* системно".

Представленные ниже примеры могут показаться надуманными, когда их читаешь в книге. Но представьте, что вы с коллегами присутствовали у доски в момент создания и диаграммы появлялись в процессе живого общения. Именно так мы трактуем "мыслить" системно.

###### Нотации и примеры

Диаграммы причинно-следственных связей содержат много элементов; приведённые ниже общие полезные элементы будут использоваться дальше в сценарии.

* переменные
* причинные связи
* обратные эффекты
* ограничения
* цели
* реакции; скороспелые реакции
* эффекты взаимодействия
* экстремальные воздействия
* задержки
* петли положительной обратной связи
{: .two_columns .box_top_bottom}


*Ниже приведён упрощённый сценарий для конкретной организации. Не рассматривайте это как общий случай.*

**Переменные**{: style="color: #1997C0"}---Диаграммы причинно-следственных связей включают *переменные* (или метрики), такие как *скорость разработчики (стоимость доставки) фич* и *количество дефектов*. Переменные имеют измеримую величину.

![systems thinking-4.png](/img/systems_thinking/systems%20thinking-4.png)

**Причинно-следственные связи**{: style="color: #1997C0"}---Один элемент может влиять на другой, например, если скорость разработки фич увеличивается, количество дефектов также увеличивается; то есть, чем больше нового кода, тем больше дефектов.

![systems thinking-5.png](/img/systems_thinking/systems%20thinking-5.png)

Теперь пришло время нам встретиться с *Законом Вайнберга-Брукса* и *Ловушкой причинно-следственной связи*. Легко нарисовать диаграмму; но совсем другое - построить её с пониманием. Например, рассмотрим связь между *количеством разработчиков* и *скоростью разработки фич*.

Природа любой причинно-следственной связи на самом деле не очевидна, хотя это очень свойственно людям - прийти к заключению, что увеличение количества разработчиков приводит к увеличению скорости разработки фич. Но добавление людей на поздних стадиях разработки может *уменьшить* скорость (один из элементов “Закона Брукса” [Brooks95]). Или: *больше* плохих разработчиков могут здорово вас замедлить. Можно сделать вывод, что *устранение* ужасных разработчиков может *улучшить* скорость.

![systems thinking-6.png](/img/systems_thinking/systems%20thinking-6.png)

**Обратные эффекты**{: style="color: #1997C0"}---Эффект от причинно-следственной связи может быть прямым или обратным; если А растёт, то растёт и В, или наоборот. Обратный эффект показан символом ‘O’ рядом с линией. Предположим, рост количества дефектов в системе приводит к замедлению скорости разработки новых фич, потому что люди тратят больше времени на исправление дефектов иил поиск обходных путей.

![systems thinking-7.png](/img/systems_thinking/systems%20thinking-7.png)

**Ограничения**{: style="color: #1997C0"}---До тех пор, пока вы не придумали где найти людей, согласных работать бесплатно, у вас есть ограничение на количество разработчиков, которых вы можете позволить себе нанять, исходя из вашей прибыли.

Ограничения - это *не* причинно-следственные связи. Даже если ваша прибыль вырастет, количество разработчиков не увеличится.

![systems thinking-8.png](/img/systems_thinking/systems%20thinking-8.png)

**Цели и реакции**{: style="color: #1997C0"}--Люди, подразделения и системы имеют цели, такие как *увеличение скорости разработки фич*. Цели часто заставляют людей реагировать (или действовать) с намерением достичь цель. Но, принимая по внимание *Ловушку причинно-следственной связи* и *Закон Вайнберга-Брукса*, необходимо быть осторожными, полагая, что действия могут помочь. Цель и порождённые ей действия показаны на рисунке:

![systems thinking-9.png](/img/systems_thinking/systems%20thinking-9.png)
 
Цель с *наградой* заставляет не только действовать, но и порождает *видимость* действия и достижения, из-за **дисфункции измерения**, вызванной наградами. И дисфункция измерения может быть пропорциональной воспринимаемой ценности награды, потому что люди мотивированы получить награду, а не улучшить систему [[Austin96]](http://www.amazon.com/Measuring-Managing-Performance-Organizations-Dorset-ebook/dp/B00DY3KQX6/ref=sr_1_1?ie=UTF8&qid=1413596674&sr=8-1&keywords=measuring+and+managing+performance+in+organizations). Обратите внимание, как награды могут привести к деградации производительности системы. Визуально, системная динамика может быть такой...

![systems thinking-10.png](/img/systems_thinking/systems%20thinking-10.png)

Интересно, что вся эта системная динамика появилась из-за введения награды, и пока нет никакой связи между верхней и нижней частями этой модели.

Нет никаких гарантий, что скорость разработки фич улучшилась --- или даже что на неё что-то повлияло.

Отказ от системы наград - решение корневой причины дисфункции измерений. Другое (менее предпочтительное), лежащее на поверхности решение - это принцип поведения бережливого мышления *Сходи Посмотри* (физически сходить и посмотреть на место, где выполняется реальная работа):

![systems thinking-11.png](/img/systems_thinking/systems%20thinking-11.png)

**Временные решения**{: style="color: #1997C0"}---Одно из сложных и медленных решений в достижении цели увеличения скорости разработки фич - нанять крутых разработчиков, увеличить степень обучения и коучинга текущей команды, уволить ужасных сотрудников. Альтернатива - так называемое *временное* решение, основывается на быстром достижении цели с минимальными усилиями. Иногда такое решение работает в кратко- и долгосрочной перспективе, действительно укрепляя систему. Но "иногда" не значит "следовательно", "Тише едешь – дальше будешь" ... Например, люди могут *верить*, что увеличение количества разработчиков увеличит скорость разработки фич. И, тем самым, они могут надеяться, что найм большего количества разработчиков - самый быстрый и простой способ решить проблему со скоростью разработки. Символы ‘QF’ обозначают временное решение:

![systems thinking-12.png](/img/systems_thinking/systems%20thinking-12.png)

**Эффекты взаимодействия**{: style="color: #1997C0"} --- Фонд оплаты труда является ограничением для найма. Одно из сложных и медленных решений - зарабатывать больше денег. Временное решение - нанять *очень дешёвых* разработчиков. В этом случае наша прибыль оказывает *эффект взаимодействия* на другие причинные связи. Низкая прибыль вынуждает нас нанимать меньше разработчиков, в то время как нам нужно больше.

Кто-то мог бы просто нарисовать (обратную) причинную связь напрямую из *прибыли* к *процент нанятых очень дешёвых разработчиков*, но вряд ли можно сказать, что уменьшение прибыли приводит к найму большего числа очень дешёвых разработчиков. Это не совсем то, что мы хотим сказать; скорее, мы хотим показать эффект взаимодействия---что взаимодействие А влияет на "взаимодействие" B. Это можно показать, если одну причинную связь подвести к другой причинной связи. Например, от *прибыли* к стрелке, изображающей временное решение, приводящее к *нанимать больше очень дешёвых разработчиков*:

![systems thinking-13.png](/img/systems_thinking/systems%20thinking-13.png)

**Сильное воздействие**{: style="color: #1997C0"} --- Мы работали с очень крутыми, но недорогими разработчиками, а также очень дорогими, но бесполезными. Но в среднем вы получаете то, за что платите --- когда вы нанимаете людей из большого набора дешевых кандидатов, их навыки в среднем хуже. Мы хотим изобразить на диаграмме, что последствия найма более дешевой рабочей силы на *количество слабых разработчиков* намного сильнее, чем в при найме средних разработчиков.

Чтобы показать *сильное воздействие* в модели, используйте жирную линию:

![systems thinking-14.png](/img/systems_thinking/systems%20thinking-14.png)

**Задержки**{: style="color: #1997C0"}---One problem in hiring in software development is the *fallacy of mild programmer variance* ---the mistaken belief that programmer variance (in terms of productivity, code quality, etc.) is relatively small. However, programmer variance studies suggest an average of four times faster in the top versus bottom quartile [[Prechelt00]](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.43.4788). Rather significant. Also, the COCOMO model---based on large and longitudinal studies---shows that the capability of the development personnel is by far the most important factor for productivity [[Boehm00]](http://www.amazon.com/Software-Cost-Estimation-Cocomo-II/dp/0130266922/ref=sr_1_1?ie=UTF8&qid=1413597244&sr=8-1&keywords=Software+Cost+Estimation+with+Cocomo+II). And, on average, very weak programmers create poor-quality code (poor design) and more defects, creating another drag on the system.

But the impacts of these effects are not immediately obvious. For example, it takes a relatively long time after hiring a large pool of weak programmers before the impacts of more and more bad code/design start to be felt. Similarly, the average *decrease* in feature velocity (because of the powerful impact of programmer variance) will not show up immediately.

To show these *delayed effects* in the model, use a double-line through the effect line:

![systems thinking-15.png](/img/systems_thinking/systems%20thinking-15.png)

Delay has an intriguing influence on the *educational* or corrective power in a system. If an impact or unintended consequence is long delayed, one does not feel the effect (pain or gain) and so does not clearly see how A influenced B, or more subtly how *A influenced B influenced A* .

Therefore, one does not learn from or correct mistakes---in policy, management actions, tools, and so forth. Likewise, gradual improvement through the lean thinking practice of *kaizen* can take a long time; patience and insight are needed to see if and how things improve.

**Петли положительной обратной связи**{: style="color: #1997C0"}---Петли отрицательной или положительной обратной связи<sup>[5](#footnote-5)</sup> и задержки---это те вещи, которые делают систему и её понимание более сложными. Например, как можно стать более квалифицированным разработчиком? В частности, путём наставничества у лучших программистов и изучения большого количества качественного кода. Но, если в команде работает много низкоквалифицированных разработчиков, неоткуда взяться качественному коду, и вряд ли в такой команде будут работать крутые разработчики, у которых можно учиться. Они предпочтут работать где-то в других местах.

Такая команда попадает в самоусиливающуюся нисходящую спираль---из-за набора *петель положительной обратной связи*. К счастью, нисходящий тренд ограничен фондом заработной платы.

Крутые разработчики, которые пишут качественный код и могут быть наставниками для остальных, уходят из команды. Это приводит к тому, что качественного кода, на который можно смотреть и учиться, становится всё меньше и меньше. Слабых разработчиков становится ещё больше и скорость разработки фич продолжает падать. Код становится менее понятным и поддерживаемым, в нём увеличивается количество повторений, что ухудшает возможность быстрой реализации фич. Дальнейшее падение скорости производства фич вынуждает нанимать всё больше дешёвых разработчиков. Всё это приводит к появлению множества петель положительной обратной связи в системе, например:

![systems thinking-16.png](/img/systems_thinking/systems%20thinking-16.png)

*Совет* : Найти петли положительной обратной связи можно, найдя циклы с *чётным количеством* обратных эффектов. В модели выше есть несколько таких примеров.

##### Заключение

Приведённый пример---это только пример. Диаграмма причинного цикла может наглядно показать богатую динамику на рабочем месте. Лучше всего создавать диаграмму вместе у доски.

## Seeing Mental Models

The previous causal loop diagrams reflect people’s mental models of causation, which may be wrong. It is interesting to note that people’s models of causation are influenced by the timeliness (delay) and quality of feedback in the system.

The implication of “mental models” is to improve our meta-cognitive skill to see and question our own assumptions and chains of reasoning. Are we making faulty leaps of logic? It also implies when working with others to discuss (inquiring rather than abusing) the mental models of our colleagues.

*Seeing* these mental models is step one; *changing* them is the even harder part of step two. That art is beyond the scope of this introduction, though a successful LeSS adoption must involve changes in mindset and insight among many groups.

A tip to better *see* the mental models (beliefs, chains of inference, ...) playing out in the system dynamics is to ask the following question during a modeling workshop and then sketch the answers. “Let’s talk about the assumptions behind this model. What do we *believe* or assume in terms of facts and effects that led us here?”

Answers are sketched on the whiteboard model, for example:

<figure>
  <img src="/img/systems_thinking/systems%20thinking-17.png" alt="systems thinking-17.png">
  <figcaption>Visualizing the assumptions in our heads... our mental models.</figcaption>
</figure>

### Example: The “Faster is Slower” Dynamic

With the vocabulary of quick fixes, delays, positive feedback loops, and mental models, it is fascinating to see that there can be a short-term apparent improvement in a variable as the result of a quick fix, but a *delayed degradation* of the very same variable---the “faster is slower” dynamic. This is a recurrent dynamic in the workplace and a cause of weakness. So it is worth another illustration.

*The story of Microsoft Word and the* ***secret developer toolbox*** : A classic example of the short-term ‘improving’ but long-term degrading dynamic is the story of the first release of Microsoft Word for Windows [[Spolsky04]](http://www.amazon.com/Joel-Software-Occasionally-Developers-Designers/dp/1590593898/ref=sr_1_1?ie=UTF8&qid=1413597951&sr=8-1&keywords=Joel+on+Software). It was released *years* later than desired. Why? *Because managers tried to follow the original schedule and pushed developers to meet it* .

The story illustrates why *wishful thinking* is identified as one of the wastes in lean thinking. In this case the wishful thinking of insisting on (apparently) following a schedule, which implies the misconception or wishful thinking that development estimates are not estimates but are commitments---a common myth that propels degradation of a system.

[The next model](#figure-1) illustrates a *summary* of the dynamics of what happened when the managers pushed people to evidently keep to the original schedule, and why this quick-fix reaction to slow progress appeared to make things faster in the short term but actually even *slower* in the long term. See the dynamic of schedule pressure and the secret toolbox. intentionally omits some deeper dynamics that are expanded and shown in See deeper dynamics of schedule pressure and the secret toolbox..

<a name="figure-1"></a>
<figure>
  <img src="/img/systems_thinking/systems%20thinking-18.png" alt="systems thinking-18.png">
  <figcaption>The dynamic of schedule pressure and the secret toolbox.</figcaption>
</figure>

As a quick fix, the Microsoft managers exhorted, bribed (with potential rewards), and threatened the Word developers to keep to the original schedule. Consequently, the developers predictably pulled out their **secret developer toolbox** ---the many practices related to hacking out dirty code (no tests, no reviews, ignore known defects, copy-paste programming, poor design, ...) to apparently deliver a feature faster. You see, developers also have *quick-fix* reactions for their problems.

The tactics seemed to have worked like magic. As the managers pressured the developers, ‘features’ were delivered quicker as people used the secret toolbox, which reinforced the belief that pressuring developers helps. But this apparent acceleration actually had a delayed effect to make things slower, which is explored next. Since management did not quickly see the delayed effect of the secret toolbox, and because they believed managers should not be frequently looking in detail at the source code or themselves be master programmers, they did not learn from this dynamic.

A closer exploration of the system dynamics shows why things went slower in the long term and why the first Word for Windows release was years later than desired, illustrated in this model...

<a name="figure-2"></a>
<figure>
  <img src="/img/systems_thinking/systems%20thinking-19.png" alt="systems thinking-19.png">
  <figcaption>Some deeper dynamics of schedule pressure and the secret toolbox.</figcaption>
</figure>

Naturally, lots of dirty code eventually slowed things down. More subtly, developers would *ignore* the bug list of ever-increasing open defects to---instead---generate new features. This led to a long delay between the creation of a defect and its correction. It turns out that this significantly increases variability and time to fix a defect because of the compounding negative effect of a long-lived bug (for example, due to workarounds and coupling) and because developers have long forgotten the detailed context of code related to the defect and therefore need to slowly rediscover that context---with more and more dirty confusing code surrounding them.

The astute reader may also notice the several positive feedback loops that reinforce the degradation cycle; this is one reason the product was years later than intended.

Solution? The lean thinking *Stop and Fix* and *Go See* principles. *First* , rather than trying to go faster when there are problems, manager-teachers encourage people to go *slower* and help them learn to see system dynamics and root causes, and to fix these---to improve the *system* of development. By going slower, Toyota---the masters of lean thinking---has become one of the fastest companies around. *Second* , for managers to *go see at the real place of work* to learn what is going on. The “real place” in software development is the code, which suggests that first-level managers are master programmers who are frequently evaluating the code.

Microsoft people did not reflect on the situation until after release. When they did finally hold a retrospective, it led to a *zero-defects* policy, meaning that the first priority was to fix known bugs in the code under development---to drive down to zero the open-defects list before writing more new-feature code.


## Seeing (and Hearing) Local Optimization

“Everyone is doing their best yet overall systems throughput is degrading. How can that be?” This is the paradox of **local optimization** ---when a person or departmental decision maker optimizes for the local view or self-interest. The party making the decision frequently *believes they are making the best decision* , but because ‘best’ is a local optimization, in fact it sub-optimizes overall system throughput. This is a result of “silo mentality,” misunderstanding, fear, limited information, delayed feedback, ignorance, careerism, avarice, and other common *organizational learning disorders* .

A small product group of 30 people does not have the time or money to engage in much nonsense or waste. But large companies, with large product groups, centralized process and tool groups, a centralized “project management office,” and so forth, seem to have raised local optimization and waste to an art form. Government bureaucracies are the quintessential example, of course. As such, when you serve as a guide in large-scale agile adoption, *seeing* (or *hearing* ) and dealing with local optimization is singularly vital.

For example, the legal and corporate security departments put in place a policy that seems terribly important from their perspective. In the aim of preventing loss of intellectual property (IP), the legal department decrees “no one shall put any information on the walls.” Or, in response to cost-cutting pressure, the facilities management says, “It is important to ensure our walls are not dirty or damaged.” And thus they shut down a practice in lean thinking, visual management (which is usually done on walls), and they inhibit a well-known innovation practice, group whiteboard work. The lawyers may succeed in reducing loss of IP (actually, that is questionable), and the facilities people will succeed in keeping the walls clean---at the cost of inhibiting the product development group from innovating and collaborating. Finally, the company falls behind with less and less IP even worth protecting because tools for innovation and delivering fast have been disallowed, but the lawyers have successfully fulfilled their mandate from the executive team to “ensure our IP is protected.” And the *furniture police* have clear walls. *They have done their best* .

The following is a real e-mail quote from the *FURNITURE POLICE* in one organization that dissallowed visual management on the walls. Can you identify the local optimizations and mental models driving this?

> *Individual work cubic partition can be personalized. But things obvious higher than the partition or harming the office environment’s harmony are restricted.*

We also see local optimization in centralized groups that make software tool choices for others. The common mindset is to choose a tool that is best at reducing some supposed cost (curiously, these groups seldom recommend free open source tools) or best at doing something complicated or best for the work of one specialized worker role (even though *everybody* has to use the tool), rather than maximizing the global goal of faster system throughput of value to customers.

In large-scale adoption of Scrum or agile principles, most of the “Yes, but ...” issues that are raised are examples of local optimization, such as, “*Yes, but...what about management reporting*?” or more generally, “*Yes, but...what about <special case>*?” Then, policies and practices are twisted around, serving the goal of reporting or some other secondary aim rather than the primary goal of optimizing for fast value throughput. Sometimes we see *local optimization for the extreme or rare case* . For example, a person responsible for making a centralized tool choice for the enterprise presents a scenario for a complex or rare case of use, and then chooses the tool that fits that, sub-optimizing for a 5 percent case instead of optimizing for ease and speed for the 95 percent case.

Other local optimizations are due to ignorance of new ways of working. This is especially common in large-scale product groups. For example, we once helped a large networking product group in Europe adopt Scrum and the practice of *continuous integration* (CI) combined with a CI system that continually integrated, built, and automatically tested the product. After some time, an outside traditional manager inspected what was going on, and recommended the integration practices should be changed---because there was no written integration plan for how a human integration manager should manually integrate all the software, and of course, there was no integration manager. They wanted to ‘optimize’ around the work of an integration manager that was no longer needed. They could not see that their entire old-fashioned model of work had been eliminated with CI. This story repeats in all the departments of a large established product: local optimization around the *existing* ways of work, such as manual test, a separate architecture department, component teams, and so on. A coach working to introduce large-scale Scrum at the enterprise level has a *mountain* of similar local optimization thinking to deal with.

In lean thinking and agile methods, the focus is on global systems goals: Deliver value fast with high quality and morale---**global optimization** . Try to consider decisions in light of this goal. To develop an “optimize the whole” culture, challenge all decisions and policies with the question:

> **Does this decision or policy focus on delivering value to the external customer fast, or does it focus on the interests of a department, person, internal policy/practice, or rare case?**

In LeSS, the Product Owner is responsible for choosing high-value goals that **could lead to potentially shippable product (at the end of the Sprint) and that maximize the desired impacts and that delight the customer, while maintaining a sustainable pace and high engineering quality**. That explicit goal is meant to orient the system toward global rather than local optimization.

## Conclusion

In addition to becoming a systems thinker yourself, encourage others to learn more about this topic. We suggest you to try getting together at a whiteboard with colleagues to sketch a causal loop diagram, so that *being* systems thinkers and *doing* systems thinking are connected at the workplace.

<figure>
  <img class="rounded shadowed" src="/img/systems_thinking/group%20cld%20modeling.jpg" alt="group%20cld%20modeling.jpg">
  <figcaption>Doing system thinking. Sketching a causal loop diagram together—modeling to have a conversation.</figcaption>
</figure>

## Recommended Readings

* W. Edwards Deming’s [*Out of the Crisis*](http://www.amazon.com/Out-Crisis-W-Edwards-Deming-ebook/dp/B00653KTES/ref=sr_1_1?ie=UTF8&qid=1413601625&sr=8-1&keywords=out+of+the+crisis) is a master work by arguably the most well-known systems thinker and quality expert. It opens with the modest goal, “The aim of this book is transformation of the style of American management... It requires a whole new structure, from foundation upward.” Deming also advocates the *System of Profound Knowledge* in which managers (1) appreciate there is a *system* , (2) understand common-cause and special-cause variation (queueing theory is related to variation), (3) understand limitations of knowledge and reasoning mistakes, and (4) know credible psychology and social research results so that behavior- or motivation-related policies are *not* based on “common sense.” The core of the book centers around his famous *14 Points for Management* , including (for example), “*Eliminate management by objective. Eliminate management by numbers, numerical goals. Substitute leadership* .” <br>
* Jay Forrester’s [*Industrial Dynamics*](http://www.amazon.com/Industrial-Dynamics-Jay-Wright-Forrester/dp/1614275335/ref=sr_1_1?ie=UTF8&qid=1413601681&sr=8-1&keywords=industrial+dynamics) is the classic text on system dynamics---well written and insightful. Although written in the early 1960s, it is as relevant today as when published. It goes beyond cause-effect modeling to also model the flow and inventories of information, money, and material in systems. The book includes formal mathematical modeling but this is not obligatory to appreciate system dynamics.
* Weinberg’s *Quality Software Management: Systems Thinking* and *An Introduction to General Systems Thinking* are worthwhile. Written from the perspective of an experienced consultant in systems development.  <br>
* Senge’s [*The Fifth Discipline*](http://www.amazon.com/Fifth-Discipline-Practice-Learning-Organization-ebook/dp/B000SEIFKK/ref=sr_1_1?ie=UTF8&qid=1413601715&sr=8-1&keywords=the+fifth+discipline) is a classic that advocates the need for leadership to apply systems thinking (it is the *fifth* discipline) and other key disciplines for a great, sustainable enterpise. The others include leaders with (1) personal mastery and (2) reflection on their beliefs and faulty reasoning, the (3) definition and communication of a meaningful shared vision, and (4) the ability of teams to learn. We recommend ignoring---at least during the first few years of practice---the ‘archetypes’ notion presented in the book. It was well meant as a learning aid but has been observed to distract and intimidate people from learning and applying basic system dynamics modeling. The ‘archetypes’ are not part of original system dynamics.  <br>
* [*The Fifth Discipline Fieldbook*](http://www.amazon.com/Fifth-Discipline-Fieldbook-Strategies-Organization-ebook/dp/B00JTCJEO8/ref=sr_1_1?ie=UTF8&qid=1413601809&sr=8-1&keywords=The+Fifth+Discipline+Fieldbook) is an in-depth resource, written from the viewpoint of many practitioners and consultants.  <br>
* The organizational-learning writings from Argyris, Putnam, McLain, and Schön. Important concepts include *double-loop learning* and *high-advocacy/high-inquiry dialogue*. Classic works include [*Action Science*](http://www.actiondesign.com/resources/research/action-science) and [*Organizational Learning*](http://www.amazon.com/Organizational-Learning-Addison-Wesley-Organization-Development/dp/0201001748/ref=sr_1_11?ie=UTF8&qid=1413601940&sr=8-11&keywords=organizational+learning).  <br>
* The publications and resources available through the [*Society for Organizational Learning*](https://www.solonline.org).

---

##### Notes:

<a name="footnote-1"></a> 1. Senge wrote *The Fifth Discipline* , on systems thinking and learning organizations, named “one of the seminal management books of the last 75 years” by the *Harvard Business Review.* See** [Senge94].
<br>
<br>
<a name="footnote-2"></a>2. Another reason: Believing more control is possible than actually is. Complexity science suggests fundamental limits on predicting and controlling semi-chaotic social systems [Stacey07]. This is a rather large can of worms that will remain unopened in this book.
<br>
<br>
<a name="footnote-3"></a>3. Macroeconomics, psychology, sociology, and biology are exceptions, among many others.
<br>
<br>
<a name="footnote-4"></a>4. ‘Basic’ does not mean trivial or easy to solve. For example, ‘motivation’ and ‘quality’ are basic but not easy issues.
<br>
<br>
<a name="footnote-5"></a>5. *Feedback loops* is occasionally used in this book in the colloquial sense of feedback, rather than this system dynamics sense.

