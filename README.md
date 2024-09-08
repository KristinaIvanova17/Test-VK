# Test-VK
Требования к мобильному приложению
Основные требования:
Мини-приложения:
Прогноз погоды в текущей геолокации.
Текущий город.
Кроссворд.
Крестики-нолики.
Дизайн:
Список мини-приложений, каждое занимает 1/8 высоты экрана и 100% ширины (неинтерактивный режим).
Список мини-приложений, каждое занимает 1/2 высоты экрана и 100% ширины (интерактивный режим).
Полноэкранное отображение одного мини-приложения (интерактивный режим).
Логика работы:
Возможность взаимодействия с мини-приложением в интерактивном режиме.
Количество мини-приложений в списке должно быть не менее 10.
Флоу приложения:
Определение порядка отображения и логика переходов между экранами на усмотрение разработчика.
Дополнительные возможности:
Использование менеджеров управления зависимостями (CocoaPods/SPM).
Пакеты для CocoaPods и/или SPM для мини-игр.
Разные стили оформления одного и того же мини-приложения.
Особое внимание:
Отказ от использования SwiftUI.
Адаптивный дизайн для iPhone и iPad, поддержка поворота экрана на iPad.
Возможность повторного использования мини-приложений.
Однородность оформления и структуры кода.
Использовать внешние библиотеки только для вспомогательных операций (сеть, хранение данных и т.д.).
Для реализации данного проекта на iOS можно использовать такие фреймворки и библиотеки, как UIKit, CoreLocation для определения геолокации, Alamofire или URLSession для работы с сетью, SDWebImage для загрузки изображений, и т. д.

Ниже приведен пример структуры проекта на Swift с использованием UIKit и навигации по контроллерам:
