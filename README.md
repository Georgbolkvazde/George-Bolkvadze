#Projekts 
#Projekta uzdevums ir izveidot vienkāršu paroles pārvaldīšanas programmu, izmantojot Python. Programma piedāvā funkcionalitāti, kas ļauj lietotājam ērti pārvaldīt un generēt paroles dažādām tīmekļa vietnēm un lietotājiem.

Funkcionalitātes un apraksts:
Paroles Ģenerēšana:
Lietotājs var ģenerēt drošas paroles, izvēloties garumu un izvēloties, vai tās būs "vienkāršas" vai "sarežģītas" (ar simboliem un cipariem).
Paroļu Pievienošana:
Lietotājs var pievienot un glabāt paroles, norādot tīmekļa vietu, lietotājvārdu un paroli.
Paroļu Atgūšana:
Lietotājs var atgūt saglabātās paroles, ievadot tīmekļa vietu un lietotājvārdu.
Paroļu Dzēšana:
Lietotājs var dzēst saglabātās paroles, norādot tīmekļa vietu un lietotājvārdu.
Paroļu Parādīšana:
Lietotājs var apskatīt visas saglabātās paroles tabulārā formātā, ietverot tīmekļa vietni, lietotājvārdu un paroli.
Darbību žurnāls:
Programma uztur darbību žurnālu, kur tiek reģistrētas visas veiktās darbības, piemēram, kad tika pievienota, dzēsta vai atgūta parole.
Twilio SMS Paziņojumi:
Ja tiks dzēsta parole, programma izsūta SMS paziņojumu, izmantojot Twilio API, lai informētu lietotāju par izmaiņām.
Bibliotēkas un izmantojamās tehnoloģijas:
PrettyTable:
Tiek izmantota, lai vizuāli sakārtotu un parādītu paroles tabulu.
Random un String:
Tiek izmantotas, lai ģenerētu drošas paroles ar gadījuma simboliem un burtiem.
Twilio API:
Tiek izmantots Twilio API, lai nosūtītu SMS paziņojumus paroles izmaiņām.
Darbības virkne:
Lietotājs izvēlas darbību no izvēlnes (paroļu skatīšana, pievienošana, dzēšana utt.).
Atbilstoši lietotāja izvēlei tiek veikta attiecīgā darbība (paroļu ģenerēšana, pievienošana, dzēšana utt.).
Veiktā darbība tiek reģistrēta darbību žurnālā.
Ja tiek dzēsta parole, tiek izsūtīts SMS paziņojums ar Twilio API palīdzību.
Papildu piezīmes:
Programma izmanto izolētu klasi (PasswordManager), lai pārvaldītu paroles un uzturētu darbību žurnālu.
Kods ir izstrādāts pēc objektorientētās programmēšanas principiem.
Izmantojot .env failu, tiek nodrošināta droša konfigurācija, piemēram, Twilio API atslēgas.
Šis projekts piedāvā vienkāršu risinājumu paroļu pārvaldībai un izmanto praktiskus Python rīkus un bibliotēkas, lai piedāvātu vērtīgu lietotājam.
