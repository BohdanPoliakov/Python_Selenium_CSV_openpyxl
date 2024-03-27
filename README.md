Problēmas apkasts:

Informāciju par uzņēmuma darbinieku algām glabājās speciālajā grāmatvedības programmā. Analītikas nodaļa katru mēnesi analīzē uzņēmuma darbību un arī informāciju par darbinieku algām.

Uzņēmums, lai samazinātu informācijas noplūdes risku ir pieņēmis lēmums, ka datu analītiķiem tiek nodrošināta tikai viņiem nepieciešama informācija. Rezultātā no grāmatvedības programmatūras tika eksportēta Excel datne salary.xlsx, kur klienta vārds un uzvārds ir kodēts izmantojot uzņēmuma izstrādāto kodēšanas algoritmu.

Sistēmas kļūdas dēļ vienā dienā uzņēmums ir pazaudējis piekļuvi grāmatvedības sistēmā esošajiem datiem par pēdēja mēneša darbinieku algām.

IT nodaļa risinot problēmu ir konstatējusi, ka dati sistēmā vairs nav pieejami, bet ir pieejama pēdējā analītikas nodaļai sagatavota datne salary.xlsx, kas ietver darbinieka pilnā vārda kodējuma numuru un algu. Diemžēl datnē saglabāts darbinieka vārds ir kodēts, izmantojot kodēšanas algoritmu, kas neļauj atkodēt vārdu atpakaļ.

Uzņēmumā strādā 100 darbinieki un algas failā ir 739 ieraksti. Ir zināms, ka kāds no darbiniekiem ir veicis vairākas darbības, kā rezultātā algas failā darbinieks var paradīties vairākas reizes; Informācija par darbinieka algu nebūs atrodamā algas datnē, ja darbinieks kādā mēnesī nav pildījis darbu.

Lai varētu atkodēt informāciju, ir iespēja izmantot tīmekļa kodēšanas rīku https://emn178.github.io/online-tools/crc32.html, kas nodrošina informācijas kodēšanu ar CRC32 algoritmu. (nav informācijas vai Algoritms nav modificēts, ka rezultātā var izmantot tikai kodēšanas rezultātu no tīmekļa platformas.)

Jūsu uzdevums ir izstrādāt programmu, kas:

    Atver people.csv datni lasīšanai un nolasa pilno darbinieka vārdu uz saraksta datu struktūru izmantojot Python programmēšanas valodu.
    Izmantojot Selenium bibliotēku, ir nepieciešams iegūt katra darbinieka pilnā vārda kodēšanas rezultātu izmantojot https://emn178.github.io/online-tools/crc32.html tīmekļa riku.
    Identificēt kāda ir kopēja alga katram darbiniekam. Informācija par algām tiek saglabāta failā salary.xslx, kur A kolonnas vērtība ir darbinieka pilnais vārds kodēta formātā.
    Pēc programmas izveides ir nepieciešams atbildēt uz testa jautājumiem noradot prasīto informāciju par darbinieka algām.

Kad programma ir izpildīta, jums ir nepieciešams iesniegt programmas failu <studenta ID numurs.py> formatā E-studiju vidē.
