# Final-project-encoding-go

## Описание
Этот проект на языке Go предназначен для перекодирования данных между форматами JSON и YAML. Он использует пакеты `encoding` и `utils`
## Установка
Для установки проекта и необходимых зависимостей выполните следующие команды:

```bash
go get github.com/Yandex-Practicum/final-project-encoding-go/encoding
go get github.com/Yandex-Practicum/final-project-encoding-go/utils

## **Основные функции**
Encode(data encoding.MyEncoder) error: Функция, которая принимает интерфейс MyEncoder и вызывает метод Encoding() для перекодирования данных.
main(): Основная функция, которая создает тестовые файлы JSON и YAML, а затем перекодирует данные из одного формата в другой.

## Конфигурация
Проект не требует специальной конфигурации. Для работы необходимо наличие файлов jsonInput.json и yamlInput.yml, которые создаются с помощью утилит из пакета utils.

## Контакты
Автор - Альбина Коновалова

Этот файл README.md предоставляет основную информацию о проекте, его установке и использовании, а также инструкции по вкладу и лицензии.
