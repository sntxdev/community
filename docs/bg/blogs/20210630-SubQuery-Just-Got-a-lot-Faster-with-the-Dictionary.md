# Подзаявката стана много по-бърза с речника

![](https://miro.medium.com/max/1400/1*iEQbr-KZNIkztylVowAuaQ.png)

Днес ние сме горди да обявим нашето ново подобрение на SubQuery, функцията за индексиране на речник на SubQuery.

Речникът на SubQuery е свързан с ускоряване на вашите проекти. Той драстично подобрява индексирането на производителността на вашия SubQuery Project, **понякога до 10 пъти по-бързо.**

Когато индексират верижни данни, SubQuery Projects се използва за проверка на всеки блок. Веригата на Polkadot е голяма, 130 GB неструктурирани данни в почти 6 милиона блока Това отнема много часове за индексиране, време, което не искате да чакате – особено при тестване.

Проектите на SubQuery вече имат опцията да пропускат всичко това, ние по същество предварително индексираме местоположението на всички събития във веригата.

![](https://miro.medium.com/max/1400/1*uIjz8W4TG9Q0au9zoKbHVw.png)

Производителността се подобрява най-много, когато данните не са често срещано явление, а вместо това са разпръснати по веригата, сякаш данните са редки, речникът пропуска повече блокове и следователно въздействието върху производителността е по-голямо.

Крайната точка на речника може да бъде добавена във [вашия файл „project.yaml“](https://doc.subquery.network/create/manifest.html) или алтернативно [посочена по време на изпълнение](https://doc.subquery.network/run/run.html#using-a-dictionary). Освен това можете също да замените тази крайна точка, когато изпълнявате своя проект в [Проекти на подзапитвания](https://project.subquery.network/).

![](https://miro.medium.com/max/1400/1*xl4wENAv_oNingDQZyrtyw.png)

Можете да прочетете повече за речника в нашата [полезна документация тук](https://doc.subquery.network/run/run.html#using-a-dictionary).

Вярваме, че SubQuery е най-добрата опция за индексиране на данни, налична за всяко Polkadot/Substrate dApp, и тази нова реализация на SubQuery's Dictionary ни позволява да подобрим допълнително нашата услуга, като ускорим процеса на индексиране за вашите SubQuery проекти.

Можете да опитате сами в [Проекти за подзапитвания](https://project.subquery.network/) или да видите самите речници в [нашия изследовател](https://explorer.subquery.network/). За да използвате речник във вашия съществуващ проект, вашата версия [@subql/cli](https://www.npmjs.com/package/@subql/cli) трябва да е поне 0.10.0

![](https://miro.medium.com/max/1400/1*CrbWsx1rFiBNjkCepxbkPQ.png)