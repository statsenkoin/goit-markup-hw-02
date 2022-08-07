# goit-markup-hw-02

    Пояснення до ДЗ №2.

    Приблизно такий код очікується за додатковими умовами ментора.
    body {
    --color-background-primary:#ffffff;
    --color-background-secondary: #f5f4fa;
    --color-background-footer: #2f303a;
    --color-text-primary: #757575;
    --color-text-title: #212121;
    --color-text-contacts: rgba(255, 255, 255, 0.6);
    --color-text-secondary: #ffffff;
    --color-logo: #000000;
    --color-accent: #2196f3;
    --color-card-border: #eeeeee;
    --color-header-line: #ececec;

    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 1.71;
    letter-spacing: 0.03em;
    color: var(--color-text-primary);

    background-color: var(--color-background-primary);
    }

    Виділять окремо h1-h3 сенсу немає, оскільки всі елементи мають
    різні налаштування за виключенням h2:
    .activity-title, .team-title {...}   =  h2 {...}

    .footer-line {} i .hero {} не зводив, хоча вони ідентичні,
    оскільки .hero {background-color:...} буде замінено на якийсь
    медіаконтент.
