### DDEV helpers

    // issues Win11 - resolve.conf gets rewrited
    // https://askubuntu.com/questions/1347712/make-etc-resolv-conf-changes-permanent-in-wsl-2
    sudo nano /etc/resolv.conf

    // no cache install plugin 
    ddev composer require wpackagist-plugin/all-in-one-video-gallery --no-cache
    ddev composer require wpackagist-plugin/fakerpress --no-cache
