# Bullet Ballet
Bullet Ballet - это игра, 2D шутер с видом сверху с противостоянием 2 игроков. За определённое время нужно набрать как можно больше очков. Сражайтесь, набирайте очки, ставьте рекорды и становитесь победителем!

![1](https://github.com/Zmeewik/BalletBullet/assets/74759106/757bb47e-45aa-4c85-b207-376420434d84)

![4](https://github.com/Zmeewik/BalletBullet/assets/74759106/e8be97aa-35ba-47ba-9423-eb0ed17dbd68)

## Описание
+ В игре представлен один режим игры противостояние, в котором два игрока стреляя по друг другу зарабатывают очки
+ В конце матча, кто набрал больше очков побеждает, может получиться и ничья
+ Направление стрельбы не определяется игрком, прицел вращается вокруг него, а игрок выбирает момент, когда начать стрельбу
+ Во время матча можно упать в пропасть, но за это будут списаны очки
+ В статистику записываюся общее количество всех набранных очков, максимальная цепочка устранений игроком без смертей и наибольшее количество очков за 1 матч
## Управление
Управление игрой производится путём компьютерной мыши (или другого указательного устройство ввода) и клавиатуры. Используются следующие клавиши ввода:

1. **Клавиатура**:
	+ Клавиши “W” (вверх), “A” (влево), “S” (вниз), “D” (вправо) для задания вектора направления движения 1 игрока;
	+ Клавиши стрелок “↑” (вверх), “←” (влево), “↓” (вниз), “→” (вправо) для задания вектора направления движения 2 игрока;
	+ Клавиша “V” для начала стрельбы 1 игрока;
	+ Клавиша “P” для начала стрельбы 2 игрока;
	+ Клавиша “ESC” для выхода в меню из настроек и статистики, для выхода в меню из игры в качестве игровой паузы и возвращения обратно в игру, продолжая с момента паузы;
	+ Клавиша “R” для быстрого перезапуска матча.
	+ Сочетание клавиш “Alt” + “F4” для моментального выхода из игры.
2. **Мышь**:
	1. Левая кнопка мыши для выбора действий в меню.

Для более удобной ориентации в игре, всегда отображается количество FPS (кадров в секунду) для понимания оптимизации проекта, а непосредственно во время игрового процесса количество набранных игроками очков и оставшееся время игровой сессии (матча).

## Ориентация в меню: 
+ **Основной экран**:
	+ Start – начать игру с текущими настройками;
	+ Continue – продолжить остановленную игру (нет функционала, если игра ещё не начата);
	+ Stats – переход в меню статистики и рекордов;
	+ Options – переход в меню настроек;
	+ Quit – выход из игры.

![2](https://github.com/Zmeewik/BalletBullet/assets/74759106/d7c911e6-4535-48d2-aa93-50e913cee673)

+ **Меню статистики и рекордов**:
	+ All points – общее количество заработанных очков игроками за все матчи;
	+ Max points – максимальное количество очков заработанных игроками в рамках одного матча;
	+ Kill streak – максимальное количество устранений, произведённое одним игроком другого без выведения из строя другим игроком.
	+ Back – вернуться в основное меню;
	+ Статистика для 1 игрока обозначена «P1», для 2 игрока «P2».

![5](https://github.com/Zmeewik/BalletBullet/assets/74759106/a90dfeae-c7e1-4fb3-b360-9e5a492fdc91)

+ **Меню настроек**:
	+ FPS limit – ограничение скорости обновления внутриигрового изображения в метрике кадр/секунда (10, 30, 60, 120, 150, 200, unlimited (неограниченное количество));
	+ Sound – изменение звука (on/off (включен/выключен));
	+ Music – изменение музыки (on/off (включен/выключен));
	+ Match duration – длительность матча в секундах (10, 30, 60, 120, 240);
	+ Back – вернуться в основное меню.

![3](https://github.com/Zmeewik/BalletBullet/assets/74759106/462c61e1-6e62-4862-8e3d-15002ebb6969)

PS: Перенос и добавление статистики происходит при завершении противостояния и выводе итогового результата, кто победил, по итогу матча. Сохранение настроек и статистики происходит при выходе из игры.

## Установка
1. Скачать и распаковать архив **Bullet Ballet.rar** в отдельную папку
2. Открыть в Visual Studio файл проекта: **Game\BulletBallet.sln**
![image](https://github.com/Zmeewik/BalletBullet/assets/74759106/f3b0f0d4-9570-4f1d-a54d-3605a06cb500)
3. Открыть в Visual Studio C++ файл: **BulletBallet.cpp** с помощью обозревателя решений
![image](https://github.com/Zmeewik/BalletBullet/assets/74759106/6e31250b-9f13-45bc-8cdf-ab25822f17cf)
4. Запусить файл: **BulletBallet.cpp**
