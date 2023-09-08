Anse — это полностью оптимизированный пользовательский интерфейс для чатов с искусственным интеллектом.

## Функции

- **🚀 Мощная система плагинов**. Работает на базе плагина Provider, легко расширяет платформы искусственного интеллекта, такие как [OpenAI](https://openai.com/), [Replication](https://rescribe.com/ ), а также поддерживает пользовательские параметры модели.
- **💬 Сохранение записи сеанса** - Мы используем IndexDB для хранения локальных данных, они не будут загружены на сервер, проблемы безопасности гарантированы.
- **🎉Режимы нескольких сеансов** - Обеспечивает различные режимы разговоров, поддерживает «Одиночный разговор», «Непрерывный разговор», «Генерацию изображений OpenAI», «Стабильное распространение» и многое другое.
- **💎 Улучшенный пользовательский интерфейс**. Мы провели рефакторинг пользовательского интерфейса веб-сайта для предыдущей версии, оптимизировали множество деталей, а также адаптировали его для мобильных устройств и темного режима.
- **🌈 Развертывание в один клик** - Поддержка развертывания в один клик, отказ от использования переменных среды. Вы можете обратиться к нашей документации для развертывания веб-сайта в [Vercel](https://vercel.com/), [Netlify] (https://www.netlify.com/), `Docker`, `Node` и другие платформы.

## Запуск локально

### Предварительная среда
1. **Узел**: убедитесь, что и ваша среда разработки, и среда развертывания используют Node v18 или более позднюю версию. Вы можете использовать [nvm](https://github.com/nvm-sh/nvm) для локального управления несколькими версиями узла.。
   ``` баш
    node -v
   ```
2. **PNPM**: мы рекомендуем использовать [pnpm](https://pnpm.io/) для управления зависимостями. Если вы никогда не устанавливали pnpm, вы можете установить его с помощью следующей команды:
   ``` баш
      npm i -g pnpm
   ```
3. **OPENAI_API_KEY**: перед запуском этого приложения вам необходимо получить ключ API от OpenAI. Вы можете зарегистрировать ключ API по адресу [https://beta.openai.com/signup](https://beta.openai.com/signup).

### Начиная

1. Установите зависимости
   ``` баш
     pnpm install
   ```
2. Запустите приложение, локальный проект запускается на `http://localhost:3000/`.
   ``` баш
     pnpm run dev
   ```
3. Добавьте свой [ключ OpenAI API](https://platform.openai.com/account/api-keys) на панель настроек и наслаждайтесь!

## Как развернуть
Более подробную информацию можно найти в этом документе: https://docs.anse.app/self-deploy.

## Включить автоматические обновления

После разветвления проекта вам необходимо вручную включить рабочие процессы и действие синхронизации исходного кода на странице «Действия» разветвленного проекта. После включения автоматические обновления будут планироваться каждый день:

Вопрос: Ошибка типа: не удалось получить данные (невозможно подключиться к OpenAI API).

О: Ссылка: https://github.com/anse-app/chatgpt-demo/issues/34.

Вопрос: выдать новый TypeError(`${context}` не является ReadableStream.)

О: Версия Node должна быть v18 или новее, ссылка: https://github.com/anse-app/chatgpt-demo/issues/65.

Вопрос: Ускорить внутренний доступ без необходимости обучения по развертыванию прокси-сервера?

О: Вы можете обратиться к этому руководству: https://github.com/anse-app/chatgpt-demo/discussions/270.

## Вклад

Этот проект существует благодаря всем, кто внес свой вклад.

Спасибо всем нашим сторонникам!🙏

Contributing
This project exists thanks to all those who contributed.

Thank you to all our supporters!🙏

img

License
MIT © ddiu8081

About
Supercharged experience for ChatGPT, DALL-E and Stable Diffusion.

anse.app
Topics
openai gpt-3 dall-e gpt-4 stable-diffusion chatgpt gpt-35-turbo
Resources
 Readme
License
 MIT license
Security policy
 Security policy
 Activity
Stars
 1.4k stars
Watchers
 13 watching
Forks
 313 forks
Report repository
Releases 12
v1.1.11
Latest
on Jul 10
+ 11 releases
Packages
No packages published
Contributors
15
@ddiu8081
@yzh990918
@CNSeniorious000
@chancelyg
@tsui66
@ninvfeng
@eltociear
@CaoYunzhou
@YuJian920
@Nikit-Singh
@LyuLumos
@Dippery
+ 4 contributors
Deployments
167
 Production 4 months ago
 Production – anse 2 days ago
 Preview – anse 3 days ago
+ 164 deployments
Languages
TypeScript
92.4%
 
CSS
4.1%
 
JavaScript
1.7%
 
Astro
1.7%
 
Dockerfile
0.1%
