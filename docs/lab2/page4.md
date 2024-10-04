# Задание 2. Config

В этом файле хранятся константы с числом процессов, классы и теги для обработки содержания веб-страниц и
URL-адреса для парсинга. 

### Код

    URLS = [
    'https://skillbox.ru/media/management/kak-stat-prodaktmenedzherom-i-nuzhno-li-dlya-etogo-obrazovanie/',
    'https://skillbox.ru/media/management/produktovyy-analitik-chem-on-zanimaetsya-skolko-zarabatyvaet-i-kak-im-stat/',
    'https://skillbox.ru/media/code/qainzhener-kto-eto-chem-on-zanimaetsya-i-kak-im-stat/',
    'https://skillbox.ru/media/management/kto-takoy-restorator-skolko-on-zarabatyvaet-i-kak-im-stat/',
    ]

    NUM_THREADS = 4
    HTML_CLASS = 'stk-reset stk-theme_26309__style_large_header'
    HTML_TAG = 'h2'