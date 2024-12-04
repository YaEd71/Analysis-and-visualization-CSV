### **Основные особенности реализации экспорта данных в CSV:**

1. Проверка типов входных данных
2. Автоматическое добавление расширения .csv
3. Предупреждение о перезаписи существующего файла
4. Возможность отмены экспорта
5. Информативные сообщения об ошибках
6. Сохранение индекса (дат) в CSV-файл

При запуске программы пользователь получит дополнительный запрос на экспорт данных в CSV-файл после построения графика.

Рекомендации по использованию:
- Пользователь может ввести:
   - Утвердительные варианты: "да", "yes", "y"
   - Отрицательные варианты: "нет", "no", "n"
   - Любой другой текст

- Если пользователь вводит что-либо, кроме "да", "yes" или "y", либо любой другой текст  - экспорт **НЕ происходит**
- Файлы CSV будут сохраняться в той же директории, где запускается скрипт
- Названия файлов формируются автоматически на основе тикера и периода

Таким образом, пользователь всегда имеет выбор: экспортировать данные или нет.

Результаты работы программы представлены на скиншотах ниже:

Пример реализации экспорта данных в CSV c использованием PyCharm для акции GOOGL с периодом 6 месяцев, представлен на рисунке 1:

![Googl-csv](https://github.com/user-attachments/assets/f2221242-395c-4813-90ae-0e6465b2b73a)
*Рисунок 1 Реализация экспорта данных в CSV для акции GOOGL с периодом 6 месяцев*

Пример визуализации c использованием PyCharm для акции GOOGL с периодом 6 месяцев, представлен на рисунке 2:

![Googl-6mo](https://github.com/user-attachments/assets/8ee3e947-f74c-4855-9ea8-66c0df427e2f)
*Рисунок 2 Визуализация для акции GOOGL с периодом 6 месяцев*

Этот проект отлично демонстрирует возможности Python для финансового анализа с использованием библиотек yfinance, pandas и matplotlib.
