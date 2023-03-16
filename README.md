---
title: "MD Syntax"
date: "22.02.2023"
desc: "Символы '---', указанные в начале, заключают в себе метаданные .md файла"
---

---
# Заголовок-1
## Заголовок-2
### Заголовок-3
#### Заголовок-4
##### Заголовок-5

---
### Список
- Пункт 1
- Пункт 2
- Пункт 3

---
### Чек-лист
- [ ] Пункт 1
- [x] Пункт 2
- [ ] Пункт 3

---
### Ссылки
[Link](https://learn.javascript.ru/)

![Alt text | 400](https://kartinkin.net/pics/uploads/posts/2022-08/1660356464_13-kartinkin-net-p-melburn-stolitsa-avstralii-krasivo-foto-13.jpg) 

[Ссылка к элементу данной страницы (в браузере работает только для заголовков первого уровня)](#Заголовок-1)

---
### Таблица
|Столбец 1     |Столбец 2     |
|--------------|--------------|
|Пункт 1       |Пункт 2       |

---
### Сноска
> Пункт 1<br>Пункт 2<br>Пункт 3<br>

---
### Подробное описание
Текст с переходом к подробному описанию[^1]

[^1]: Подробное описание (автоматически размещается в самом низу страницы)

---
### Блок кода
```javascript
function loadScript(src) {
	let script = document.createElement('script');
	script.src = src;
	document.head.append(script);
}
```

---
### Несколько пробелов и переносов строк
Текст&nbsp;&nbsp;с&nbsp;&nbsp;&nbsp;несколькими&nbsp;&nbsp;&nbsp;&nbsp;пробелами
<br>
<br>
<br>
и переносами

---
###  Сворачиваемый текст
<details>
	<summary style="cursor: pointer;">Нажмите чтобы развернуть</summary>
	<ul style="margin-top: 10px;">
		<li>Скрытый текст 1</li>
		<li>Скрытый текст 2</li>
		<li>Скрытый текст 3</li>
	</ul>
</details>

---
###  Mermaid
Mermaid - простой язык для составления блок-схем
```mermaid
graph TD
	A-->B
    A-->C
    B-->D
    C-->D
```

---
###  Дополнительно
[Канал с уроками по Obsidian](https://www.youtube.com/@dy-sh)
[Горячие клавиши, плагины и прочее](https://github.com/dy-sh/obsidian-wiki)





