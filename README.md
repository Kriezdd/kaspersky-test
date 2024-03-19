# Выбор слов из .csv файла

## (gh-pages: https://kriezdd.github.io/csv_words_selector/)

### Используемый инструментарий:
<p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/4/47/React.svg" alt="react-logo" width="30"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/Typescript_logo_2020.svg" alt="ts-logo" width="30"/>
  <img src="https://static-00.iconduck.com/assets.00/ant-design-icon-512x512-xbdsnx83.png" alt="antd-logo" width="30"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/640px-CSS3_logo_and_wordmark.svg.png" alt="css-logo" width="28"/> 
</p>

### Принцип работы:
1) Загрузите один .csv файл с помощью соответствующей кнопки
2) В таблице ниже появятся строки. В этих строках вы можете выделить с помощью мыши интересующие вас слова или снять выделение повторным нажатием мыши (выделять можно только слова, без знаков препинания)
3) После выделения необходимых слов вы можете сохранить их в новый .csv файл с помощью соответствующей кнопки ниже таблицы. В файле будут представлены слова сгруппированные теми же строками, строки разделены через "|" 

# ТЗ: 
Инструментарий JS (желательно TS), React, MobX (по необходимости), Ant Design
Написать приложение, выполняющее следующий функционал:
1) По нажатии кнопки «Load» открывается диалог выбора файла .csv
CSV файл содержит строки на русском и английском языке (тестовый файл для отладки
можно создать самому, при проверке программе будет передан заранее сформированный
файл от заказчика)
2) Файл распарсивается на отдельные строки и каждая строка отображается в таблице в
отдельной строке
3) Пользователь с помощью мышки при нажатии на слово может его, а при повторном
нажатии снять выделение
4) При нажатии кнопки «Save» в отдельный файл сохраняются выбранные слова (через
разделитель “|”) для каждого предложения (если в предложении не выбрано никакого
слова, то и в файл ничего для данной строки не записывается)

---

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).