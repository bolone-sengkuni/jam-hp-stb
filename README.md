# jam-hp-stb


wget --no-check-certificate "https://raw.githubusercontent.com/vitoharhari/syncdate-openwrt-for-modemhp/main/syncdate-hp" -O /usr/bin/syncdate-hp && chmod +x /usr/bin/syncdate-hp

lalu klik enter,dan tunggu sampai proses selesai
lalu masukkan command ini di Luci, masukkan di system>startup>local startup ,atau jika di terminal di rc.local
sleep 10 && /usr/bin/syncdate-hp
