# Template проекта на CRA с TS и FSD

## Оглавление

- [Дополнительные библиотеки](#дополнительные-библиотеки)
- [Сценарии запуска](#сценарии-запуска)
- [Автор](#автор)

## Дополнительные библиотеки

- Стили
  - [`sass`](https://www.npmjs.com/package/sass)
- Линтер
  - [`eslint`](https://eslint.org/)
  - [`eslint-config-prettier`](https://www.npmjs.com/package/eslint-config-prettier)
  - [`eslint-config-airbnb`](https://www.npmjs.com/package/eslint-config-airbnb) включая зависимости установленные командой `npx install-peerdeps --dev eslint-config-airbnb`
  - [`eslint-config-airbnb-typescript`](https://www.npmjs.com/package/eslint-config-airbnb-typescript)
  - [`eslint-config-prettier`](https://www.npmjs.com/package/eslint-config-prettier)
- Форматирование кода
  - [`prettier`](https://prettier.io/)
- Менеджеры Git hooks
  - [`husky`](https://typicode.github.io/husky/)
  - [`lint-staged`](https://www.npmjs.com/package/lint-staged)
  - [`commitizen`](https://www.npmjs.com/package/commitizen)
  - [`cz-conventional-changelog`](https://www.npmjs.com/package/cz-conventional-changelog)
- Прочии
  - [`clsx`](https://www.npmjs.com/package/clsx)

## Сценарии запуска

- `npm start` - режим разработки с запуском локального сервера
- `npm run build` - режим сборки проекта в продакшн
- `npm run test` - запуск в режиме тестирования
- `npm run eject` - режим извлечения конфигов CRA
- `npm run lint` - запускает линтер
- `npm run lint:fix` - запускает линтер, в режиме устранения мелких замечаний
- `npm run format` - запуск форматера кода
- `npm run prepare` - подготавливает Husky к работе, запускается единожды при старте проекта
- `npm run commit` - запускает commitizen для коммита

## Автор

**Данила Легкобытов**

- e-mail: [legkobytov-danila@yandex.ru](mailto:legkobytov-danila@yandex.ru)
- LinkedIn: [in/danila-legkobytov](https://www.linkedin.com/in/danila-legkobytov/)
- Telegram: [@danila_legkobytov](https://t.me/danila_legkobytov)
- Frontend Mentor: [@danila_legkobytov](https://www.frontendmentor.io/profile/Bjorn86)
