✅ AdGuard DNS uyumlu blocklist.txt içeriği:
txt
Kopyala
Düzenle
! Title: Custom AdGuard DNS Blocklist
! Description: Xiaomi, Facebook, Google, Microsoft, Samsung ve Avast telemetri/izleme alan adları
! Version: 2025.05.06
! Last modified: 2025-05-06T19:40:00Z
! Homepage: (isteğe bağlı GitHub URL'si buraya eklenebilir)

||graph.facebook.com^
||b-graph.facebook.com^
||api.facebook.com^
||z-m-gateway.facebook.com^
||z-p42-chat-e2ee-ig.facebook.com^
||chat-e2ee-mini.facebook.com^
||firebase-settings.crashlytics.com^
||firebaseremoteconfig.googleapis.com^
||firebaseinstallations.googleapis.com^
||mobile.pipe.aria.microsoft.com^
||mobile.events.data.microsoft.com^
||settings-win.data.microsoft.com^
||userlocation.googleapis.com^
||api.account.samsung.com^
||api.samsungcloud.com^
||wu2z-api.samsungcloud.com^
||dcg.microsoft.com^
||ncc.avast.com^
||ip-info.ff.avast.com^
||filerep-replica-win.ff.avast.com^
||honzik.avcdn.net^
||emupdate.bav.avcdn.net^
||in.appcenter.ms^
||googleads.g.doubleclick.net^
||census-app.scorecardresearch.com^
||tags.tiqcdn.com^
||a.nel.cloudflare.com^
||data.mistat.intl.xiaomi.com^
||mazu.sec.miui.com^
||flash.sec.intl.miui.com^
||metok-ccc.intl.xiaomi.com^
||api.hybrid.intl.xiaomi.com^
||globalapi.ad.xiaomi.com^
||api.ad.intl.xiaomi.com^
||sg.global.market.xiaomi.com^
||fp-afd.azureedge.us^
➕ Ne Yapmalısın?
Bu içeriği bir .txt dosyasına kaydet (örneğin blocklist.txt).

GitHub’da yeni bir repo oluştur ve bu dosyayı yükle.

"Raw" bağlantısını al:

arduino
Kopyala
Düzenle
https://raw.githubusercontent.com/kullaniciadi/repoadi/main/blocklist.txt
AdGuard Home > Filters > Custom Filtering List bölümüne bu URL’yi ekle.

"Apply" ve "Refresh" yap, filtre aktif olur.

İstersen bu listeyi senin için doğrudan GitHub’a yüklemen için hazır .txt dosyası olarak sağlayabilirim. Yardımcı olayım mı?







Şunu dedin:
github için bu .txt için readme ön izleme oluşturalım
ChatGPT:
Harika fikir! GitHub deposuna blocklist.txt dosyasını eklerken, onunla birlikte bir README.md dosyası eklemek, hem açıklayıcı hem de profesyonel bir görünüm sağlar. Aşağıda, senin listene özel olarak hazırlanmış bir örnek README.md ön izlemesi var:

📦 Custom AdGuard DNS Blocklist
A lightweight DNS blocklist targeting telemetry, analytics, and tracking domains from services like Xiaomi, Facebook, Google, Microsoft, Samsung, Avast, and more. Ideal for AdGuard Home and other DNS-level ad/tracking blocking setups.

📌 Features
🚫 Blocks telemetry and usage reporting domains

📉 Reduces unwanted tracking and background data

⚙️ Compatible with AdGuard Home (||domain.com^ format)

🔒 Local-first and privacy-focused

🔗 Raw List URL
Use this URL to import into AdGuard Home:

bash
Kopyala
Düzenle
https://github.com/mertumur/AdGuardHome-blocklists/blob/main/local-block-list.txt
Replace <kullaniciadi> and <repoadi> with your actual GitHub username and repository name.

🛠️ How to Use in AdGuard Home
Go to Filters > Custom Filtering Rules > Add Custom Filtering List

Paste the Raw link above

Click Apply and Refresh

🧩 Domains Included
Facebook: graph.facebook.com, api.facebook.com, ...

Xiaomi: data.mistat.intl.xiaomi.com, mazu.sec.miui.com, ...

Google/Firebase: firebaseinstallations.googleapis.com, ...

Microsoft: mobile.pipe.aria.microsoft.com, ...

Samsung: api.samsungcloud.com, ...

Avast: ip-info.ff.avast.com, ...

Diğer çeşitli takip ve reklam altyapıları...

📄 License
This list is distributed under the MIT License. Feel free to fork, modify, and use.

✍️ Maintainer
Created and maintained by [mertumur]
