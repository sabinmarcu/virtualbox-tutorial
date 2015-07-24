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
