# Resilient Web Design by Jeremy Keith

## Перевод сайта и книги
## resilientwebdesign.com

**Если часть сайта, которая в разработке, не имеет пока перевода, верстаем ее с английским текстом временно.**

Мы хотим сохранить айдентику и стиль оригинального сайта.

Список задач: *(будет пополняться)*

*Вся верстка выполняется адаптивно с анимацией, если она есть.*

- [ ] Подобрать близкую по начертанию гарнитуру к оригинальной (репозиторий со шрифтами https://edwardtufte.github.io/et-book/) и подключить к проекту шрифты через @font-face (Victor H)
- [ ] Верстка первого экрана главной страницы (Arslan)
- [ ] Верстка футера (Tatyana)
- [ ] Верстка оглавления без анимации (Anastasia K)
- [ ] Создание анимации для оглавления (ховер-эффект) (Anastasia K)
- [ ] Верстка блока с цитатами "People are saying…" на главной странице (Arslan)
- [ ] Верстка абзацев "Formats" и "Audio" (Arslan)
- [ ] Верстка первой главы (целиком или часть по договоренности) (Kristina A)
- [ ] Верстка второй главы (целиком или часть по договоренности)
- [ ] Верстка предисловия (introduction) (целиком или часть по договоренности)
- [ ] Подключить к существующему коду шрифты

### Алгоритм работы с репозиторием и ветками
##### По всем вопросам по установке пишите ментору 

- В терминале вводим команду cd ~/Desktop, чтобы сделать рабочий стол текущей директорией.
- Проверям, что сменили директорию успешно. Команда: 'pwd'
- Клонируем репозиторий: для этого в терминале пишем команду 'git clone https://github.com/moscoding/RWD.git'. Папка с названием RWD будет находиться там, где была запущена команда 
- После установки мы находимся на ветке master. Далее создаем новую ветку для задачи, команда: 'git checkout -b branch/название-вашей-части-сайта-из-задачи-через-дефис'
- Проверяем, что мы в нужной ветке. Команда: 'git branch'
- Делаем задачу, пишем код
- Для проверки или по завершении создаем commit. Добавляем файлы в git: команда 'git add -A'. Далее команда: 'git commit -m "название коммита"', называем его осознанно (например, "верстка футера")
- Затем команда: 'git push'. Копируем из того, что вернула команда ('git push --set-upstream .....то, что у вас..'), более длинную версию команды git push и запускаем.
- После успешного push`a, в терминале появится ссылка на github. После перехода по ней создаем merge request тоже с осознанным названием 
- Ждем code review от ментора, если надо, правим код 
- Ветка вливается в master