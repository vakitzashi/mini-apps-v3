# Кейс: Создание Canvas-приложений с помощью Gemini AI

## Введение

Я уже представлял несколько кейсов по прототипированию простых Canvas-приложений:
- [Прототипирование с помощью ИИ](https://github.com/vakitzashi/mini-apps-byAI)
- [Создание приложений с использованием Gemini + Firebase Studio](https://github.com/vakitzashi/mini-apps-v2)

Однако сегодня я хочу обратить внимание на возможности **Gemini AI** в создании Canvas-приложений. В отличие от функции "Артефакт" нейросети Qwen Chat, которая создаёт приложения с заранее прописанным функционалом без доступа к интернету и аппаратным возможностям устройства, **Gemini AI** предлагает значительно более широкие возможности.

---

## Возможности Gemini AI

При создании прототипов приложений **Gemini AI** может:
1. Ссылаться на внешние библиотеки.
2. Использовать библиотеки шрифтов.
3. Подключать сторонние API для обработки информации вне прописанного кода.
4. Задействовать аппаратные возможности устройства (геолокация, доступ в интернет, воспроизведение звука и вибрации) с разрешения пользователя.

Эти возможности позволяют создавать более сложные и функциональные приложения, чем те, которые генерируются другими ИИ, такими как **Qwen**, **ChatGPT** и аналогами.

---

## Примеры Canvas-приложений, созданных с помощью Gemini AI

Вот несколько тестовых приложений, которые я разработал для изучения возможностей Gemini AI:

### 1. **Compressor**
Простое приложение для сжатия изображений с целью уменьшения их веса. При сжатии более чем на 5 пунктов качество изображения значительно ухудшается, но до 5 пунктов оно остаётся приемлемым.

![Compressor 1](https://github.com/vakitzashi/mini-apps-v3/blob/main/compress1.png)

Результат компрессии на 5 пунктов:

![Compressor 2](https://github.com/vakitzashi/mini-apps-v3/blob/main/compressed.png)

---

### 2. **Music Visualizator**
Пользователь загружает аудио-файл, и приложение создаёт визуализацию в виде столбчатой частотной диаграммы в реальном времени. Такое же приложение можно реализовать с использованием звука с микрофона.

![Music Visualizator](https://github.com/vakitzashi/mini-apps-v3/blob/main/visual1.png)

---

### 3. **Sequensor**
Простой музыкальный loop-пад, который зацикленно воспроизводит выбранные пользователем ноты в заданном BPM.

![Sequensor](https://github.com/vakitzashi/mini-apps-v3/blob/main/seq1.png)

---

### 4. **QR-code Generator**
Приложение генерирует QR-код из текста, введённого в поле ввода. Используется внешняя библиотека. Есть функция сохранения сгенерированного QR-кода.

![QR-code Generator](https://github.com/vakitzashi/mini-apps-v3/blob/main/QRgen1.png)

---

### 5. **Gravitation**
Приложение для демонстрации гравитационного воздействия на частицы. Не рекомендуется генерировать более 5000 частиц. Пользователь может изменять гравитацию в реальном времени и наблюдать её влияние на частицы.

![Gravitation](https://github.com/vakitzashi/mini-apps-v3/blob/main/grav1.png)

---

### 6. **Dolce Gusto Timers**
Приложение для владельцев кофеварки Dolce Gusto без функции отсчёта времени. Помогает выполнить точный пролив для приготовления кофе. Дополнительные сорта можно легко добавить вручную через код (в коде оставлены пояснения) или попросить ИИ сделать это. По окончании приготовления приложение издаёт звук и воспроизводит вибрацию смартфона.

![Dolce Gusto Timers](https://github.com/vakitzashi/mini-apps-v3/blob/main/dgt1.png)

![Dolce Gusto Timers2](https://github.com/vakitzashi/mini-apps-v3/blob/main/dgt2.png)

---

### 7. **Wallpaper Generator**
Генератор минималистичных обоев. Пользователь может выбрать от 1 до 5 разных цветов на спектре и применить один из 17 типов смешения этих цветов. Есть возможность сохранить полученное изображение.

![Wallpaper Generator](https://github.com/vakitzashi/mini-apps-v3/blob/main/wall1.jpg)

---

## Заключение

Таким образом, **Gemini AI** благодаря задействованию большего числа библиотек, ссылок на внешние базы шрифтов и использование аппаратных возможностей устройства способен создавать более сложные и функциональные приложения, чем **Qwen**, **ChatGPT** и многие другие известные ИИ.

Эти примеры демонстрируют, как искусственный интеллект может быть использован для быстрого прототипирования и создания приложений с уникальным функционалом. Это открывает новые горизонты для разработчиков, дизайнеров и энтузиастов, желающих экспериментировать с минимальными затратами времени и ресурсов.
