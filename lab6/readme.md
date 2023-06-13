# Применение средств и методов OSINT

## Цель работы
* Освоить базовые подходы процессов OSINT
* Освоить инструменты совместной работы в ходе аналитической деятельности
* Освоить современные инструменты поиска и сбора информации

## План выполнения
1. Собрать информацию о профильных компаниях в сфере ИБ и их продуктах
2. Собрать информацию об основных специализированных технологиях, применяемых в средствах защиты информации.
3. Собрать информацию о публичных сотрудниках, ведущих профильные технологические блоги, профили в социальных сетях и т.д.
4. Сформировать представление о рынке отечественных решений ИБ 

## Ход работы
Собрать публичную информацию о компании Positive Technologies

1. Полное название компании Акционерное общество «Позитив Текнолоджиз» -  ведущий разработчик решений для информационной
безопасности. Технологии и сервисы используют более 2300 организаций
по всему миру, в том числе 80% компаний из рейтинга «Эксперт-400». 
2. Структура компании:
    * Компания строится по матричному принципу, созданы программно-целевые группы во главе с руководителем проекта, которые подчиняются высшему руководству компании.
3. Основные направления деятельности компании
   * Защита веб-приложений
   * Контроль защищенности инфраструктуры 
   * Выявление инцидентов ИБ в инфраструктуре, включая закрытые промышленные системы
   * Реагирование на киберугрозы как на конечных точках, так и в инфраструктуре в целом, объединяя для верификации атаки события и контекст из множества систем ИБ
   * Обнаружение уязвимости и ошибки в приложениях, а также поддержание процесса безопасной разработки
   * Обнаружение и отражание целевых и массовых атак с применением современного вредоносного ПО
   * Детектирование атак во внутреннем и внешнем трафике компаний
 4.  Производимые продукты, основные сферы их применения, их достоинства
      * MaxPatrol VM - управление IT-активами компании
         * MaxPatrol VM сканирует IT-активы в режимах черного и белого ящика, импортирует данные из других решений ИБ и внешних каталогов.
         * Позволяет учитывать значимость для бизнес-процессов защищаемых активов и сконцентрироваться на работе с приоритетными узлами.
         * Классифицирует и группирует активы для автоматизации процесса управления уязвимостями.
      * MaxPatrol SIEM - MaxPatrol Security Information and Event Management дает полную видимость IT-инфраструктуры и выявляет инциденты информационной безопасности. Он постоянно пополняется знаниями экспертов Positive Technologies о способах детектирования актуальных угроз и адаптируется к изменениям в защищаемой сети.
         * Отслеживание общего состояния ИБ в организации
         * Получение полной видимости IT-инфраструктуры
         * Правила для выявления инцидентов - за несколько кликов
      * PT Sandbox - Сетевая песочница. Экспертный инструмент для риск-ориентированной защиты
         *  Гибкая кастомизация виртуальных сред: в них можно добавить специфическое ПО, которое действительно используется в компании и может стать точкой входа для злоумышленников
         *  Уникальная «приманка», провоцирующая вредоносное ПО совершить активные действия и выдать себя. Файлы-приманки содержат поддельные учетные записи, файлы конфигурации или другую информацию, имитирующую данные реальной инфраструктуры
         *  Настраиваемое машинное обучение, которое повышает точность выявления неизвестных целенаправленных угроз. С его помощью анализируются более 8500 признаков поведения объекта: действия процессов, цепочки последовательностей вызовов API, сетевое взаимодействие, создаваемые вспомогательные объекты.
      * MaxPatrol8 - Система MaxPatrol 8 предназначена для обеспечения контроля защищенности и соответствия стандартам безопасности информационных систем.
         * Pentest
            + Режим тестирования на проникновение реализует проверки, типичные для сканера сетевого уровня: инвентаризационные, «баннерные» проверки, фаззинг, подбор учетных записей. Также в MaxPatrol 8 есть специализированные проверки для анализа защищенности веб-приложений и СУБД.
         * Audit
            + Режим системного сканирования позволяет провести инвентаризацию аппаратного и программного обеспечения, сбор конфигурационных параметров ОС, служб, СУБД, прикладных систем и средств защиты информации, выявить уязвимости, ошибки конфигурации и контролировать обновления.
         * Compilance
            + Режим контроля соответствия стандартам позволяет проверять выполнение требований российских регулирующих органов, международных и отраслевых стандартов, корпоративных регламентов.
      * MaxPatrol O2 - Позволяет автоматически обнаружить и остановить злоумышленника до того, как компании будет нанесен неприемлемый ущерб.
         * Моделирует действия злоумышленников
         * Выявляет цепочки хакерской активности
         * Автоматизирует расследования
         * Оценивает степень опасности угроз
         * Останавливает злоумышленника
5. Используемые технологии, языки программирования и технологии обеспечения безопасности:
      * Динамический анализатор приложений
      * Многоуровневая защита от вредоносного ПО
      * Сканер уязвимостей
      * Управление инцидентами кибербезопасности АСУ ТП
      * Система анализа трафика для выявления атак
      
     + Языки программирования:
         * C++
         * JavaScript
         * Python
         * C#
         
6. Основные клиенты компании:
     * Работают с более чем 2300 клиентами, в числе которых крупные компании, финансовые организации, государственные учреждения, промышленные и сервисные компании.
     * [Список клиентов](https://www.ptsecurity.com/ru-ru/about/clients/)

7. Основные веб-сайты компании и ее продуктов:
   + Веб-сайт: [positive technologies](https://www.ptsecurity.com/ru-ru/)
8. Публичные сотрудники компании, активные участники ИТ и ИБ-сообщества, участники профильных конференций:
   + [Сотрудники](https://www.ptsecurity.com/ru-ru/about/speakers/)
9. Уникальные достижения, ключевые продукты компании (при наличии)   
   + [Премия Е+ Awards](https://www.ptsecurity.com/ru-ru/about/news/positive-technologies-poluchila-oskar-v-oblasti-marketinga-premiyu-e-awards-za-postroenie-ehffektivnyh-kommunikacij-s-roznichnymi-investorami-s-nulya/)
## Оценка результата
В результате данной практической работы мы выяснили, что Positive Technologies - это одна из ведещих компаний по разрабатыванию антивирусного ПО, с множеством продуктов, подходящих как для дома, так и для бизнеса.
## Вывод
Освоили базовые подходы процессов OSIN, современные инструменты поиска и сбора информации.