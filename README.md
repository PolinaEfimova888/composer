# composer

создаем папку с файлом composer.json 

Начинаем работу с composer


composer update

unalias $(alias | grep winpty | cut -d"=" -f1 | cut -d" " -f2)

php -r "readfile('https://getcomposer.org/installer');"|php

php composer.phar -v

composer install

Далее устанавливаем пакеты

Все пакеты устанавливались с https://packagist.org/

1. Используется БД для хранения данных. // composer require lichtner/fluentpdo

2. Используется кеш в памяти для временного хранения сложных запросов к БД. //composer require phpfastcache/phpfastcache

3. Формируются XLS-отчеты на основе данных. //composer require deivisondc/csv-xls-report-generator

4. Формируются PDF-документы на основе данных. //composer require phpoffice/phpword

5. Отправляются SMS-сообщения для верификации пользователей. //composer require doge-dev/laravel-sms-verification

6. Отправляются E-mail-уведомления и рассылки для пользователей. //composer require laravel/framework

7. Используется облачное хранилище AWS S3 или Windows Azure Blob для статичных файлов. //composer require aws/aws-sdk-php

8. Используется интеграция со службой доставки для расчета стоимости (например, PickPoint или Почта России) //composer require shiptor/shipping-calculator

9. Используется интеграция с социальными сетями для авторизации пользователей. //composer require mad-web/laravel-social-auth

10. Данные о товарах регулярно отправляются в Яндекс.Маркет. //composer require bukashk0zzz/yml-generator

11. Принимается онлайн-оплата от покупателей. //composer require swedbank-spp/swedbank-payment-portal

12. Применяются средства тестирования (например, PHPUnit). //composer require phpunit/phpunit
