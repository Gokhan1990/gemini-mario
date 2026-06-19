🍄 Gemini Mario Project
Bu proje, Google Drive üzerinden sesli komutlarla kodlanan ve GitHub Actions aracılığıyla sıfır manuel müdahale ile canlıya alınan bir "Voice-to-Deploy" otomasyon deneyidir.
🚀 Otomasyon Mimarisi
Bu depoda, Google Docs üzerindeki bir metin belgesinin (kod dosyası), GitHub Actions tarafından otomatik olarak çekilip index.html olarak derlendiği özel bir CI/CD hattı bulunmaktadır.
Nasıl Çalışır?
Giriş: Kod içeriği Google Dokümanı olarak hazırlanır.
Çekme: GitHub Actions, Google Drive API üzerinden içeriği ham metin (format=txt) olarak çeker.
Dağıtım: Çekilen kod otomatik olarak main dalına işlenir (commit) ve GitHub Pages üzerinden canlıya alınır.
🛠 Kullanılan Teknolojiler
Google Workspace API: İçerik yönetimi ve veri kaynağı.
GitHub Actions: Sürekli entegrasyon ve dağıtım (CI/CD).
Git Automation: Otomatik commit ve push işlemleri.
🔗 Canlı Link
Projenin güncel haline buradan ulaşabilirsiniz: https://gokhan1990.github.io/gemini-mario/
Geliştirici: Gökhan | Sesle yönetilen otomasyon sistemi.
