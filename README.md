# Currency Converter

Учебное приложение с функцией рассчета валют (преобразование из одной в другую), при помощи json объекта с сайта https://www.cbr-xml-daily.ru/
## Quickstart

Run the following commands to bootstrap your environment:

    sudo apt-get install -y git python-venv python-pip
    git clone https://github.com/OlgaPertsova/Currency-converter.git
    cd currency-converter

    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt

    cp .env

Run the app locally:
    
    python manage.py runserver

Run the app docker:

    git clone https://github.com/OlgaPertsova/Currency-converter.git
    cd currency-converter
    docker build . --tag docker-currency-converter
    docker images
    docker run -p 8004:8001 image_id/image_tag
