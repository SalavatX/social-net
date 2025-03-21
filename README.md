# Социальная сеть

Современная социальная сеть, разработанная с использованием React, Firebase и Tailwind CSS.

## Технологии

### Фронтенд
- React.js + TypeScript
- React Router для маршрутизации
- Tailwind CSS для стилизации
- Heroicons для иконок

### Бэкенд
- Firebase Firestore для хранения данных
- Firebase Authentication для авторизации
- YandexCloud для хранения медиа-файлов

## Функциональность

✅ Публикация постов (текст, изображения)
✅ Лайки и комментарии
✅ Авторизация и регистрация (Firebase Auth)
✅ Обмен сообщениями в реальном времени
✅ Уведомления (новые лайки, комментарии, сообщения)
✅ Профиль пользователя (аватар, имя, описание, фон, кол-во друзей и т.д)
✅ Адаптивный интерфейс для веба и мобильного

## Установка и запуск

1. Клонируйте репозиторий:
```
git clone https://github.com/yourusername/social-network.git
cd social-network
```

2. Установите зависимости:
```
npm install
```

3. Создайте проект в [Firebase Console](https://console.firebase.google.com/) и получите конфигурацию.

4. Обновите файл `src/firebase/config.ts` с вашими данными Firebase.

5. Запустите проект:
```
npm run dev
```

## Структура проекта

```
src/
├── components/         # Компоненты React
│   ├── auth/           # Компоненты аутентификации
│   ├── layout/         # Компоненты макета
│   ├── messages/       # Компоненты для сообщений
│   ├── notifications/  # Компоненты для уведомлений
│   ├── posts/          # Компоненты для постов
│   └── profile/        # Компоненты профиля
├── contexts/           # React контексты
├── firebase/           # Конфигурация Firebase
├── App.tsx             # Основной компонент приложения
└── main.tsx            # Точка входа
```

## Планы на будущее

- Сторис (как в Instagram)
- Поиск по постам и пользователям
- Темная тема
- Мобильное приложение на React Native

