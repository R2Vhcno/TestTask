# Тестовое задания

Раздел I:

1) Добавить ограничение поворота налево - файл: Задание1.osc
2) Добавить ограничение на въезд в город - файл: Задание2.osc
3) Добавить ограничение на въезд в город - файл: Задание3.osc
4) Ответ: Данный маршрут не может быть использован для большегрузов, так как проходит черз город

Раздел II:

1) Расстояние от точки до линии - папка LineDistance
2) Рисование ломанных, заданных в опр. формате - папка LineStrings

Все проекты собираются с помощью `dotnet build`, требуемая версия: .NET 8. Все зависимости установлены через NuGet.

____

### Дополнительно:

> В задании для отрисовки линии был использован OpenGL, хотя можно было использовать и Gtk с Cairo (Для кросплатформенности).

> Так как в задании для рисования ломанных сказано, что, возможно, данные не смогут поместится в ОЗУ , поэтому был выбран способ отрисовки в текстуру (во фреймбуфер)
