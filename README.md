# HidingExtractingInformationPDFfiles Курсовая работа

## 1.	Цель курсовой работы
Целью курсовой работы является разработка программы скрытия и извлечения информации в PDF-файлах.
## 2.	Задачи курсовой работы
В процессе выполнения курсовой работы:
-	Разрабатывается пользовательский интерфейс приложения;
-	Реализовывается алгоритм скрытия и извлечения информации из графических и PDF файлов с помощью языка C#;
-	Интеграция алгоритма в пользовательский интерфейс;
-	Тестирование и отладка программы;
- Подготовка отчёта по курсовой работе.
## 3.	Требования к курсовой работе
Разрабатываемый алгоритм должен поддерживать:
-	возможность выбора файла-контейнера;
-	возможность выбора файла-сообщения произвольного типа или ввода текста скрываемого сообщения;
-	контроль возможности скрытия сообщения в контейнере (сравнением их длин, например);
-	возможность шифровать/расшифровывать внедряемое/извлекаемое сообщение на ключе, выводимом из парольной фразы;
-	возможность определять при расшифровании извлекаемых из контейнера данных факт ввода неверной парольной фразы (например, путем добавления к данным перед их шифрованием и внедрением в контейнер сигнатуры – специальной строки символов – с проверкой ее наличия в расшифрованных данных и удалением из них в случае успешной проверки).
## Алгоритм скрытия информации в графических файлах - LSB (англ. Least Significant Bit — Наименее значимый бит)

