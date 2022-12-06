# jam-hp-stb
    ```
    wget --no-check-certificate "https://raw.githubusercontent.com/kulo-sinten/jam-hp-stb/main/jam-hp.sh" -O /usr/bin/jam-hp.sh && chmod +x /usr/bin/jam-hp.sh
    ```
#system>startup>local startup
sleep 10 && /usr/bin/jam-hp.sh


# jam.sh
    ```
    wget --no-check-certificate "https://raw.githubusercontent.com/kulo-sinten/jam-hp-stb/main/jam.sh" -O /usr/bin/jam.sh && chmod +x /usr/bin/jam.sh
    ```
cek koneksi setiap 1 jam, lalu me-restart vpn dan zerotier jika koneksi tidak tersedia, salin perintah dibawah ini ke **``LuCI -> System -> Schedule Tasks``
    ```
    0 * * * * /usr/bin/jam.sh tsel.me/worryfree:80
    ```


