## 🛡️ ADMIN ASSISTANT
Внутриигровой справочник для администраторов и хелперов GTA5RP.com

![Версия](https://img.shields.io/badge/version-1.0.0-blue) ![Статус](https://img.shields.io/badge/status-active-brightgreen) ![Платформа](https://img.shields.io/badge/platform-Windows-lightgrey)

# 📋 О проекте

DMIN ASSISTANT — это приложение-справочник, созданное специально для помощи администраторам и хелперам проекта GTA5RP.com. Инструмент позволяет быстро находить необходимую информацию по законодательной базе, правилам сервера и проекту в целом, не выходя из игры.

> ⚠️ Важно: На данный момент программа разработана только для администрации проекта GTA5RP (сервер LA PUERTA). Доступ к авторизации предоставляется разработчиком индивидуально.

## 🚀 Основные возможности

- ✅ Быстрый поиск:
- - Мгновенный поиск по ключевым словам в законах и правилах
- - Фильтрация по категориям и разделам

- 📚 Полная база знаний:
- - Уголовный кодекс (УК)
- - Административный кодекс (АК)
- - Дорожный кодекс (ПДД)
- - Процессуальный кодекс
- - Правила проекта и сервера (OOC/IC)
- - Готовые ответы для репортов
- - Краткое WIKI по функционалу проекта
- - Частые вопросы и ответы на обращения из репортов


## 📋 Удобные функции

- **Просмотр полной трактовки законодательства** (как на официальном форуме)
- **Информация о предусмотренных наказаниях** (IC законка и правила OOC)
- **Копирование пунктов правил, статей и наказаний одним кликом** (удобно для рапортов и оформления)
- Автоматическое обновление законодательной базы, правил проекта и сервера, памяток и готовых ответов под конкретный сервер
- Актуальные данные всегда под рукой

## 📥 Установка

Here's how to install my project:

```bash
Шаг 1: Скачать релиз
Перейдите в раздел Releases

Скачайте последнюю версию Admin.Assistant.exe

Шаг 2: Установка
Запустите скачанный файл и следуйте инструкциям установщика

При установке старой версии — приложение автоматически обновится при первом запуске

Шаг 3: Авторизация
После установки запустите приложение

Авторизуйтесь через Discord

Доступ предоставляется разработчиком индивидуально
```



## 📋 Журнал изменений

Полный список изменений и обновлений доступен в файле [CHANGELOG.md](https://github.com/Gnom4k/Admin-Assistant-GTA5RP/releases). Также Dev Blog доступен при запуске приложения на странице авторизации через Discord.


## ❓ Часто задаваемые вопросы (FAQ)

🎮 Почему таблица не открывается поверх игры?
Две самые частые причины:

Игра запущена в режиме "Полноэкранный" (эксклюзивный fullscreen)

В этом режиме GTA5/RAGE MP рисует изображение напрямую в буфер видеокарты в обход обычного оконного менеджера Windows

Поверх такого режима не может отобразиться ни одна сторонняя программа — это ограничение Windows/DirectX, а не баг приложения

Решение: Переключите игру на "Оконный безрамочный" (Windowed Borderless) в настройках экрана GTA5

Отсутствие прав администратора

Программа должна автоматически запрашивать права администратора при каждом запуске (окно UAC от Windows) — это нужно, чтобы иметь приоритет над GTA5/RAGE MP и корректно отображать оверлей поверх них

Решение: Если вы отклонили запрос — просто перезапустите программу и подтвердите его. Если запрос вообще не появляется — запустите ADMIN ASSISTANT вручную от имени администратора (правой кнопкой по ярлыку → "Запуск от имени администратора")

🔄 Почему не обновляется программа?
Программа проверяет наличие новой версии автоматически при каждом запуске:

Если версия на GitHub новее установленной — появится предложение обновить

Если автоматическое обновление не сработало (например, из-за антивируса, блокирующего скачивание, или отсутствия интернета в момент запуска):

Зайдите на страницу проекта на GitHub Releases

Скачайте файл из последнего релиза

Запустите его вместо старой версии — он просто заменит собой предыдущую

💡 Если проблема с автообновлением повторяется регулярно — сообщите об этом через Discord (иконка внизу справа или кнопка "Контакты" на "Главной") — так мы найдём причину быстрее.

⌨️ Хоткей F7 не открывает памятку, хотя оверлей вроде должен работать
Проверьте тумблер "Оверлей памятки" на странице "Главная" — если он выключен, F7 не сработает намеренно

Убедитесь, что авторизация пройдена — без входа через Discord оверлей не открывается в принципе

📊 Таблица правил не загружается
Проверьте, что подключение к интернету стабильное

Зайдите в "Памятка правил" и нажмите кнопку "Обновить таблицу принудительно" — это сбросит кэш таблицы и перезагрузит её заново

🔐 При входе пишет, что нет роли администратора, хотя роль есть
Проверьте, что бот приглашён именно на тот сервер Discord, ID которого указан в настройках приложения

Убедитесь, что ID роли указан без лишних символов (просто число, без <@&...>)

Попробуйте выйти и авторизоваться заново

⚙️ Изменил хоткей или прозрачность в настройках, но при следующем запуске всё сбросилось
Проверьте, что нажали именно "Сохранить", а не "Отмена" или кнопку "Назад" — без явного сохранения изменения не записываются на диск и остаются только на время текущего запуска программы.

📤 Как передать свои настройки другому администратору
Нажмите кнопку "Экспорт" внизу слева — текущие настройки (хоткеи, прозрачность и т.д.) сохранятся в отдельный файл

Отправьте этот файл другому администратору

Он нажимает "Импорт" и выбирает полученный файл — его программа настраивается точно так же

📬 Куда сообщать о проблемах, которых нет в этом списке?
Через иконку Discord в правом нижнем углу приложения

Или через кнопку "Контакты" на странице "Главная"

Обе кнопки ведут в один и тот же личный Discord разработчика.



## Feedback

I'd love your input! Please:

- Open issues on [my GitHub repo](https://github.com/me/my-repo/issues)
- Email me directly at [readmecodegen@gmail.com]
- Tweet me [@mytwitterhandle]

I appreciate all feedback!



## Support

Need help with my project?\
Contact me via:

- [GitHub Issues](https://github.com/me/my-repo/issues)
- [My Support Email](mailto:readmecodegen@gmail.com)
- [Community Discord](https://discord.gg/myserver) I maintain



## Authors

I developed this project with support from:

- [@myusername](https://github.com/myusername) - Lead developer
- [@collaborator](https://github.com/collaborator) - Feature contributor



## Appendix

Additional resources I recommend:

- [Related article I found useful]
- [Technical deep dive documentation]
- [Inspiration sources]



## Documentation

I've created detailed documentation here:\
[Documentation Site](https://my-docs.site)

My documentation covers:

- Core concepts I implemented
- API usage examples
- Troubleshooting tips I've discovered



## Security

If you discover a security vulnerability, please do NOT open a public issue.\
Email me directly at [security@yourdomain.com] with details.

I follow responsible disclosure and will respond within 48 hours.



## Performance

Benchmark results on my machine (specs: [CPU/RAM]):

| Operation | Before | After | Improvement |
| --- | --- | --- | --- |
| [Task 1] | 200ms | 45ms | 77% faster |
| [Task 2] | 1.2s | 300ms | 75% faster |

Run benchmarks yourself:

```bash
npm run benchmark
```



## Troubleshooting

**Common issues I've seen and how to fix them:**

#### Error: `Cannot find module 'xyz'`

```bash
# Fix: reinstall dependencies
rm -rf node_modules
npm install
```

#### Issue: App crashes on startup

Check your `.env` file has all required variables from [Environment Variables](#environment-variables).

#### Issue: Tests failing locally

```bash
npm run test -- --clearCache
```



## GitHub Stats

![Repo Stats](https://github-readme-stats.vercel.app/api?username=YOURUSERNAME&show_icons=true&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOURUSERNAME&layout=compact)



Made with ❤️ by ReadmeCodegen.
