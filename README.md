お問い合わせフォーム

環境構築
Dockerビルド
1.git clone git@github.com:kumazawa-daisuke/test-contact.git
2.docker-compose up -d --build
※MySQLは、OSによって起動しない場合があるのでそれぞれのPCに合わせてdocker-compose.ymlファイルを編集してください。

Laravel環境構築
1.docker-compose exec php bash
2.composer install
3..env.exampleファイルから.envを作成し、環境変数を変更
4.php artisan key:generate
5.php artisan migrate
6.php artisan db:seed

使用技術
・PHP 7.4.9
・MySQL 8.0
・Laravel 8.0
・NginX 1.21.1

ER図
![test-confirm](https://github.com/user-attachments/assets/12372dcb-81f5-4a12-89d4-516c625492f9)


URL
・開発環境：http://localhost/
・phpMyAdmin：http://localhost:8080/
