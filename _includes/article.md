## Instalare

### Windows

Pentru a instala Virtual Box, accesați [pagina de download](https://www.virtualbox.org/wiki/Downloads) și descărcați versiunea pentru Windows, _VirtualBox 5.0 for Windows hosts_. Pașii de instalare sunt descriși în imaginile ce urmează:

[![Instare virtual box pas 1](assets/images/virtualbox/windows/install-step1.png)](assets/images/virtualbox/windows/install-step1.png)

[![Instare virtual box pas 2](assets/images/virtualbox/windows/install-step2.png)](assets/images/virtualbox/windows/install-step2.png)

[![Instare virtual box pas 3](assets/images/virtualbox/windows/install-step3.png)](assets/images/virtualbox/windows/install-step3.png)

[![Instare virtual box pas 4](assets/images/virtualbox/windows/install-step4.png)](assets/images/virtualbox/windows/install-step4.png)

[![Instare virtual box pas 5](assets/images/virtualbox/windows/install-step5.png)](assets/images/virtualbox/windows/install-step5.png)

[![Instare virtual box pas 6](assets/images/virtualbox/windows/install-step6.png)](assets/images/virtualbox/windows/install-step6.png)

La următoarea fereastră, apăsați _Install_

[![Instare virtual box pas 7](assets/images/virtualbox/windows/install-step7.png)](assets/images/virtualbox/windows/install-step7.png)

[![Instare virtual box pas 8](assets/images/virtualbox/windows/install-step8.png)](assets/images/virtualbox/windows/install-step8.png)

## Configurare avansată

Fiecare mașină virtuală creată în VirtualBox are o configurare proprie, pe care o putem accesa oricând dorim. În această secțiune vom parcurge fiecare tab din _Settings_ (se găsește imediat deasupra) și vom vedea la ce ajută fiecare setare. În primă fază, atunci când deschidem fereastra, vom vedea mai multe tab-uri:

[!Configurare avansată, general](assets/images/virtualbox/configurare_avansata/general.png)](assets/images/virtualbox/configurare_avansata/general.png)

### General

În acest tab sunt incluse configurările fundamentale. Acesta este împărțit în 3 sub-tab-uri, din care în _Basic_ putem seta numele mașinii virtuale. Sistemul de operare și versiunea acestuia, chiar dacă pot fi schimbate aparent, setările vor rămâne aceleași ca atunci când s-a cret mașina. 

In tabul _Advanced_, putem adauga calea către Snapshot-ul în care este creată mașina noastră virtuală, în secțiunea _Snapshot Folder_. În _Shared Clipboard_,  putem seta modul în care putem accesa clipboad-ul atât local, cât și în mașina virtuala. Astfel, pentru _Disabled_, clipboard-ul de pe host-ul local nu va putea fi folosit, iar pentru _Bidirectional_ va putea fi folosit. Setările _Host to Guest_ și _Guest to Host_ perminte partajarea clipboard-ului doar unidirecțional. Același lucru este și pentru _Drag'n'Drop_, doar că aici se face referire la partajarea fișierelor între host-ul local și mașina virtuală. Ultimele două checkbox-uri sunt setări cu privire la modul de vizualizare al mini toolbar-ului, si dacă dorim ca fișierele media să fie salvate sau nu.

În tab-ul _Description_ pot fi adăugate orice informații sau detalii legate de mașina virtuală.

### System

[!Configurare avansată, general](assets/images/virtualbox/configurare_avansata/system.png)](assets/images/virtualbox/configurare_avansata/system.png)

În _System_, se pot adăga setări pentru pentru partea hardware a mașinii virtuale. În primul sub-tab, _Motherboard_, se poate seta RAM-ul alocat mașinii, însă trebuie să avem grijă ca pe host să avem această memorie disponibilă. De asemenea, se poate seta ordinea în care vrem să se boot-eze vașina virtuală. Aceasta va funcționa la fel ca o mașină reală.




## Import / Export

### Export

Pe lângă faptul că în Virtual Box se pot crea mașini virtuale proprii, acestea pot fi și exportate, creându-se asftel copii ale unei mașini existente, ce pot fi apoi importate în alte locații. Prin exportare, sunt păstrate toate setările mașinii create, inclusiv sistemul de operare și configurările pentru RAM și CPU.

Primul pas este să deschideți Oracle VM VirtualBox Manager, iar apoi accesați din meniul principal _File_ > _Export Appliance..._. Va fi deschisă o nouă fereastră, în care trebuie să selectăm mașina ce dorim s-o exportăm, și apăsăm _Export Mode_ (în versiunile mai vechi de VirtualBox, butonul _Export Mode_ este înlocuit cu numele _Hide Description_).

[![Import pas 1](assets/images/virtualbox/export/export-step1.png)](assets/images/virtualbox/export/export-step1.png)

După ce selectăm _Export Mode_, vom vedea o fereastră ce conține detaliile mașinii virtuale. Aici trebuie să alegem locația în care dorim să ne salvăm mașina după ce va fi exportată. Aceasta va fi salvată în format .ovf sau .ova (Open Virtualization Format). Având toate acestea, putem apăsa _Export_ și asteptăm câteva minute până se copiază fișierul.

[![Import pas 2](assets/images/virtualbox/export/export-export_mode.png)](assets/images/virtualbox/export/export-export_mode.png)

La final, pentru a verifica faptul că s-a exportat totul cu succes, putem merge în locația în care ne-am dorit să fie exportată mașina. Aici vom găsi un fișier nou, care va putea fi apoi importat și folosit.

[![Import pas 3](assets/images/virtualbox/export/export-show_file.png)](assets/images/virtualbox/export/export-show_file.png)

### Import

Mașinile virtuale exportate, pot fi și importate în Virtual Box. Astfel, având un fișier în format .ovf sau .ova (Open Virtualization Format), și urmând pașii descriși în continuare, puteți avea o copie a altei mașini virtuale, ce fusese exportată.

În primul rând, deschideți Oracle VM VirtualBox Manager, iar pentru a importa, accesați din meniu _File_, apoi _Import Appliance..._. Aceasta va deschide o fereastră care va cere un fișier. Tot ce este nevoie la acest pas, este să introduceți calea către fișierul ce conține datele pentru mașina ce doriți s-o importați, apoi apasați _Next_.

[![Import pas 1](assets/images/virtualbox/import/import-step1.png)](assets/images/virtualbox/import/import-step1.png)

În fereastra următoare sunt afișate configurările setate pentru mașina virtuală. Aici puteți vedea detalii, precum numele mașinii, sistemul de operare pe care îl folosește, CPU-ul, RAM-ul. Singurele setări pe care le putem schimba noi sunt cele legate de Network, sunet, USB, DVD.

[![Import pas 2](assets/images/virtualbox/import/import-step2.png)](assets/images/virtualbox/import/import-step2.png)

[![Import pas 3](assets/images/virtualbox/import/import-step3.png)](assets/images/virtualbox/import/import-step3.png)

După ce apăsați _Import_, va dura câteva minute până se va finaliza procesul, iar apoi veți putea vedea în fereastra de VirtualBox o nouă mașină, având configurația mașinii importate. Tot ce mai rămâne este să fie pornită și folosită. De asemenea, setările noii mașini virtuale se pot accesa / modifica oricând, accesând _Settings_ din meniu.

[![Import pas 4](assets/images/virtualbox/import/import-step4.png)](assets/images/virtualbox/import/import-step4.png)
