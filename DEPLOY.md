# Деплой проекта AI CRM

Репозиторий готов к публикации. Ниже — два способа выложить сайт в интернет бесплатно.

---

## Вариант 1: GitHub Pages

1. **Создайте репозиторий на GitHub**
   - Зайдите на [github.com](https://github.com) и войдите в аккаунт.
   - Нажмите **New repository**.
   - Имя, например: `lending` или `ai-crm-landing`.
   - Не добавляйте README, .gitignore и лицензию (они уже есть локально).
   - Нажмите **Create repository**.

2. **Привяжите репозиторий и отправьте код**
   В папке проекта выполните в терминале (подставьте свой логин и имя репозитория):

   ```bash
   git remote add origin https://github.com/ВАШ_ЛОГИН/lending.git
   git push -u origin main
   ```

3. **Включите GitHub Pages**
   - В репозитории откройте **Settings** → **Pages**.
   - В блоке **Source** выберите **Deploy from a branch**.
   - **Branch**: `main`, папка: **/ (root)**.
   - Сохраните (**Save**).

4. **Сайт будет доступен по адресу:**
   `https://ВАШ_ЛОГИН.github.io/lending/`  
   (появится через 1–2 минуты после первого деплоя).

---

## Вариант 2: Netlify (загрузка папки)

1. Зайдите на [app.netlify.com](https://app.netlify.com) и войдите (можно через GitHub).
2. Перетащите папку **lending** (целиком, с `index.html`, `style.css`, `images` и т.д.) в зону **Drag and drop your site output folder here**.
3. Netlify сам определит статический сайт и выдаст ссылку вида `https://random-name-12345.netlify.app`. Её можно переименовать в настройках сайта.

---

## Что уже сделано

- Инициализирован Git, создан первый коммит.
- Ветка по умолчанию: `main`.
- Добавлен `.gitignore`.

После выполнения шагов одного из вариантов ваш лендинг будет доступен по ссылке в интернете.

---

## Если сайт не открывается (erkhanermekuly.github.io/lending_crm)

Для репозитория **erkhanermekuly/lending_crm** сделайте следующее:

1. Откройте: **https://github.com/erkhanermekuly/lending_crm**
2. Перейдите: **Settings** (вкладка вверху) → в левом меню **Pages**.
3. В блоке **Build and deployment**:
   - **Source** выберите **Deploy from a branch** (не "GitHub Actions").
   - **Branch**: выберите **main**, папка **/ (root)**.
   - Нажмите **Save**.
4. Подождите 1–3 минуты. Обновите страницу **Settings → Pages** — появится зелёное сообщение с ссылкой вида:  
   `Your site is live at https://erkhanermekuly.github.io/lending_crm/`
5. Откройте в браузере: **https://erkhanermekuly.github.io/lending_crm/**  
   (обязательно со слэшем в конце или без — оба варианта должны работать).

Если после сохранения настроек страница **Pages** показывает ошибку или "Building" дольше 5 минут — напишите, какое именно сообщение отображается.
