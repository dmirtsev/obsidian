#временная

/Users/dbashkirtsev/obsidian

## 🚀 Шаг 1: Создай Аккаунт GitHub

1. Перейди на: [https://github.com](https://github.com/)
	
2. Нажми **Sign up**
	
3. Укажи:
	
	- Имя пользователя (будет в адресе: `https://dmirtsev.github.io`)
		
	- Email
		
	- Пароль
		
4. Подтверди email и войди

---

## 🏗 Шаг 2: Установи Git На Компьютер

### 📦 Windows / Mac / Linux:

- Скачай и установи: [https://git-scm.com/downloads](https://git-scm.com/downloads)
	
- Проверь установку в терминале/командной строке:

	bash

	КопироватьРедактировать

	`git --version`

---

## 🧱 Шаг 3: Клонируй Шаблон Quartz

1. Перейди на репозиторий Quartz:
	👉 [https://github.com/jackyzha0/quartz](https://github.com/jackyzha0/quartz)
	
2. Нажми кнопку **Use this template → Create a new repository**
	
3. Назови репозиторий, например:

	КопироватьРедактировать

	`quartz-site`

4. Убедись, что стоит ✅ **Public**
	
5. Нажми **Create repository**

---

## 🧲 Шаг 4: Клонируй Репозиторий К Себе На ПК

Открой терминал и введи:

bash

КопироватьРедактировать

git clone https://github.com/dmirtsev/obsidian.git 
cd obsidian

## 🛠 Шаг 5: Настрой сайт

Файлы для заметок — внутри папки `content`.

/Users/dbashkirtsev/obsidian/content

- Удали или отредактируй `content/index.md`
    
- Добавь свои `.md` заметки (можно из Obsidian)
    

Пример:

bash

КопироватьРедактировать

`cp ~/ObsidianVault/notes/*.md ./content/`

cp "/Users/dbashkirtsev/Documents/obsidian_dm/0. Временные заметки/"*.md ./content/
