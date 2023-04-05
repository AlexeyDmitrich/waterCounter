### Программа для журналирования показаний приборов учёта водопотребления.
По сути, журнал в формате .csv с простым десктопным GUI на базе _kdialog_ для ввода данных. 

Особенности:
- [x] адаптация для работы с планировщиком crontab
- [x] защита от вероятно некорректных данных
- [x] анализ расхода

Программа была написана под использование на одном устройстве в пределах одной организации. 
Для использования в других условиях зайдите в файл _waterdata_ и отредактируйте абсолютные пути.
