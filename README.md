### Hi there 👋

<!--
**glebermon/glebermon** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


### RECENTLY COMPLETED PROJECTS

<br/>

<p style="display:flex">
    <a href="https://github.com/glebermon/employee_list">
        <img width=180 src="https://github.com/glebermon/glebermon/blob/main/employeeList.gif" />
    </a>
    <a href="https://github.com/glebermon/GMetronome">
        <img width=180 src="https://github.com/glebermon/glebermon/blob/main/GMetronome.gif" />
    </a>
    <a href="https://github.com/glebermon/LecturePlayer">
        <img width=180 src="https://github.com/glebermon/glebermon/blob/main/LecturePlayer.gif" />
    </a>

</p>
<br/>


1) Приложение - список сотркдников. Получаем данные с сервера и сохраняем результат в CoreData. В UI информация отображается из CoreData и фильтруется предикатами Есть возможность быстрой фильтрации списка с помощью табов, содержащих перечень специальностей. Можно производить поиск и сортировать по алфавиту или дням рожденя (сотрудники, чей день рождения уже только в следующем году отображаются в нижней секции).

2) Простой метроном с использованием SwiftUI 

3) Приложение - лекторий. 
- Onboarding через PageViewController с сохранением состояния показа в UserDefaults(если приложение только установленно или было обновлено - покажем, в остальных случаях сразу на главный экран).
- Главный экран - таблица со списком лекций. 
- Expandable секция (можно свернуть). 
- Фильтрация записей через switch (все записи или избранные). 
- Добавление в избранное через swipe ячейки. 
- Миниплеер над TabBar с возможность останавливать и проматывать записи. По тапу на свободную область миниплеера открывается полноценный плеер с элементами управления воспроизведением. 
- Навигация по приложению реализована через TabBar. 
- Имеются встроенные платежи.
- Реализован таймер, который через заданный интервал отключает воспроизведение
