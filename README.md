REDME Projekts nosaukums:Paroles Menegers

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

#Programmatūras izmantošanas metodes ir atkarīgas no konkrētajām darbībām, ko lietotājs vēlas veikt. Šeit ir aprakstītas galvenās darbības, kuras lietotājs var veikt, izmantojot šo programmu:

Parādīt visas paroles:
Izmantojot komandu "1", lietotājs var izvadīt visu saglabāto paroļu sarakstu ar attiecīgajām tīmekļa vietām un lietotājvārdiem.
Pievienot paroli:
Izmantojot komandu "2", lietotājs var pievienot jaunu paroli. Programma vaicās lietotājam ievadīt tīmekļa vietu un lietotājvārdu, un tad automātiski ģenerēs drošu paroli.
Dzēst paroli:
Izmantojot komandu "3", lietotājs var dzēst esošo paroli. Programma vaicās ievadīt tīmekļa vietu un lietotājvārdu, un tad dzēsīs atbilstošo paroli.
Parādīt darbību žurnālu:
Izmantojot komandu "4", lietotājs var apskatīt visus notikušos darbību žurnāla ierakstus. Šeit būs redzama informācija par katru veikto darbību, tostarp laiku un veikto darbību tekstu.
Iziet no termināla:
Izmantojot komandu "0", lietotājs var iziet no programmas un beigt darbu.
Katrs no šiem posmiem ir paredzēts, lai uzlabotu lietotāja pieredzi paroļu pārvaldīšanā un nodrošinātu drošu un efektīvu veidu, kā pārvaldīt un izmantot paroles. Lietotājs var izvēlēties atbilstošo komandu, ievadīt nepieciešamo informāciju un redzēt rezultātus terminālā vai citā interfeis
