## STEPS
- 1 Nginx container serve static html => OK
- 2 Nginx with PHP-FPM container => OK
- 3 Nginx with PHP-FPM without shared mount => WIP
    - php-fpm にパス情報を渡せていない
    - php-fpm は php 以外扱えない
    - nginx と php-fpm を分離サーバーにする場合、静的ファイルの配布方法を考えないといけない

## TODO
- Nginx の fstcgi 設定要素の理解が必要