# TRiTPO

# Требования к проекту
___
# Содержание
1 [Введение](#vvedenie) <br>
1.1 [Назначение](#naznachenie) <br>
1.2 [Бизнес-требования](#bussines_trebovanie) <br>
1.2.1 [Исходные данные](#ishodnie_data) <br>
1.2.2 [Возможности бизнеса](#vozmoznosti_bussines) <br>
1.2.3 [Границы проекта](#progect_graniza) <br>
1.3 [Аналог](#analog) <br>
2 [Требования пользователя](#trebovania_polizavatela) <br>
2.1 [Программные интерфейсы](#program_interface) <br>
2.2 [Интерфейс пользователя](#interface_polizavatela) <br>
2.3 [Характеристики пользователей](#harakteristiki_polizavatelei) <br>
2.3.1 [Аудитория приложения](#auditoria_prilozenia) <br>
2.4 [Предположения и зависимости](#predpolozenia_i_zavisimosti) <br>
3 [Системные требования](#sustemnie_trebov) <br>
3.1 [Функциональные требования](#functional_treb) <br>
3.1.1 [Основные функции](#osn_func) <br>
3.1.1.1 [Регистрация](#reg) <br>
3.1.1.2 [Сортировка товаров](#sort) <br>
3.1.1.3 [Корзина](#bag) <br>
3.1.1.4 [Заказ обратного звонка консультанта](#kons) <br>
3.1.1.5 [Оформление заказа](#pay) <br>
3.1.2 [Ограничения и исключения](#ogr_i_iskl) <br>
3.2 [Нефункциональные требования](#nef_tr) <br>
3.2.1 [Атрибуты качества](#atrib_k) <br>
3.2.1.1 [Требования к удобству использования](#isp) <br>
3.2.1.2 [Требования к безопасности](#bz) <br>

___
<a id="vvedenie"></a>
# 1 Введение
___
<a id="naznachenie"></a>
## 1.1 Назначение
Этот документ является основным источником с требованиями к сайту "AutoDoctor".
<a id="bussines_trebovanie"></a>
## 1.2 Бизнес-требования
___
<a id="ishodnie_data"></a>
### 1.2.1 Исходные данные
Невозможно отрицать, что на данный момент наиболее универсальным и независимым средством мобильности является автомобиль. Он способен доставить вас в любое место в любую погоду. Однако ничего вечного в этом мире нет. Автомобиль требует регулярного технического обслуживания. Также случается и непредвиденные поломки. Разарабатываемый интернет-магазин "AutoDoctor" должен помочь с этим. С его помощью возможно будет заказать определенные запчасти для определенного автомобиля.
<a id="vozmoznosti_bussines"></a>
### 1.2.2 Возможности бизнеса
Многие люди (как люди, лично занимающиеся ремонтом и/или обслуживанием своего автомобиля, так и работники автосервисов, станций технического обслуживания и т.д.) желают иметь возможность быстро и без привязки к определенному местоположению оформлять заказы по покупке запчастей.
Способ оформления заказа должен быть максимально простым и удобным, с минимальным
количество пользовательских данных.
<a id="progect_graniza"></a>
### 1.2.3 Границы проекта
Интернет-магазин "AutoDoctor" позволит оформить заказ на покупку запчастей в любое время, в любом месте и без существеных временных затрат.
<a id="analog"></a>
## 1.3 Аналог
___
## [AutoOstrov](https://autoostrov.by/)
___
**Русский интерфейс**: есть

**Плюсы:**
* Простой интерфейс
* Быстрая доставка
* Много пунктов выдачи заказов

**Минусы:**
* Отсутствие контроля за качеством/оригинальностью поставляемых запчастей

<a id="trebovania_polizavatela"></a>
# 2 Требования пользователя
___
<a id="program_interface"></a>
## 2.1 Программные интерфейсы
___
Интернет-магазин должен работать во всех браузерах и на всех операционных системах.
Должно быть написано на HTML5, CSS3, JavaScript ES6+.
<a id="interface_polizavatela"></a>
## 2.2 Интерфейс пользователя
___
При запуске должен быть главный экран с часто заказываемыми товарами.
![](https://github.com/romonka-l/TRiTPO/blob/main/main_page.png)
Оформление звонка.
![](https://github.com/romonka-l/TRiTPO/blob/main/call_page.png)
<a id="harakteristiki_polizavatelei"></a>
## 2.3 Характеристики пользователей
___
<a id="auditoria_prilozenia"></a>
### 2.3.1 Аудитория приложения
Люди любой возрастной категории.

<a id="predpolozenia_i_zavisimosti"></a>
## 2.4 Предположения и зависимости
___
1. Приложение не работает при отсутствии подключения к Интернету;
2. Приложение работает только в браузере;

<a id="sustemnie_trebov"></a>
# 3 Системные требования
___
<a id="functional_treb"></a>
## 3.1 Функциональные требования
___
<a id="osn_func"></a>
### 3.1.1 Основные функции

<a id="reg"></a>
#### 3.1.1.1 Регистрация
**Описание.** Пользователь может зарегистрироваться на сайте для дальнейшего удобства.

|          Функция          |                                     Требования                                     |
|:-------------------------:|:----------------------------------------------------------------------------------:|
| Регистрация пользователя  | На сайте будет две кнопки "Войти" и "Регистрация" с соответструющим функционалом.  |

<a id="sort"></a>
#### 3.1.1.2 Сортировка товаров
**Описание.** Пользователь может отсортировать товары по нужным ему критериям.

|      Функция       |                              Требования                              |
|:------------------:|:--------------------------------------------------------------------:|
| Сортировка товаров | На сайте пользователь сможет отсортировать товары по своим желаниям. |

<a id="bag"></a>
#### 3.1.1.3 Корзина
**Описание.** Пользователь может сохранять товары которы планирует приобрести.

| Функция |                                        Требования                                        |
|:-------:|:----------------------------------------------------------------------------------------:|
| Корзина | На сайте пользователь сможет добавлять в раздел "Избранное" и удалять товары которые он планурует приобрести. |

<a id="kons"></a>
#### 3.1.1.4 Заказ обратного звонка консультанта
**Описание.** Пользователь может спросить у консультанта более точную информацию о товаре.

|             Функция             |                                               Требования                                                |
|:-------------------------------:|:-------------------------------------------------------------------------------------------------------:|
| Обратный звонок от консультанта | На сайте пользователь сможет ввести свой номер, время, и товар по которому хочет получить консультацию. |

<a id="pay"></a>
#### 3.1.1.5 Оформление заказа
**Описание.** Пользователь может оформить доставку товара.

|      Функция      |                               Требования                               |
|:-----------------:|:----------------------------------------------------------------------:|
| Оформление заказа | На сайте пользователь сможет заказать товары которые добавил в корзину. |

<a id="ogr_i_iskl"></a>
### 3.1.2 Ограничения и исключения
1. Приложение не работает при отсутствии подключения к Интернету;
2. Приложение работает только в браузере;

<a id="nef_tr"></a>
## 3.2 Нефункциональные требования
___
<a id="atrib_k"></a>
### 3.2.1 Атрибуты качества
<a id="isp"></a>
#### 3.2.1.1 Требования к удобству использования
1. Интерфес должен быть понятным и простым;
2. Быстрая доставка;
<a id="bz"></a>
#### 3.2.1.2 Требования к безопасности
1. Заказ может оформить только зарегистрированый пользователь;
2. Звонок может заказать только зарегистрированый пользователь;
