TĀ NAV SAULE – mājas lapa (tanavsaule.lv)

Mapē ir viss, kas vajadzīgs. Nekas nav jābūvē vai jāinstalē – mapes saturu
augšupielādē hostingā tādu, kāds tas ir.

SVARĪGI: lapa jāskatās no hostinga (vai lokāla servera). Ja index.html atver
ar dubultklikšķi no datora, galvenā lapa rādīsies, bet skatuves mūzika neielādēsies –
pārlūks no datora faila to neļauj.

  index.html            – visa lapa: galvenā lapa + skatuve "Pamostos"
                          (skatuve atveras ar adresi tanavsaule.lv/#pamostos)
  img/                  – logo, grupas foto, plakāti, ikonas, "Pamostos" bilde
  og.jpg                – bilde, kas parādās, kad saiti iedod Facebook / WhatsApp
  pamostos/index.html   – īsā adrese tanavsaule.lv/pamostos/ (ved uz skatuvi,
                          ar savu saites bildi pamostos/og.jpg)
  pamostos/audio/       – 5 dziesmas celiņi (stems)

KAS VĒL JĀIZDARA
  Četri no sešiem koncertu plakātiem (1., 4., 5. un 6.) pagaidām tiek rādīti no vecās
  Adobe Portfolio lapas servera (cdn.myportfolio.com). Ja Portfolio lapu izslēgsi,
  tie pazudīs. Ieliec šos četrus plakātus mapē img/ un index.html failā pie
  <div class="posters"> nomaini adreses uz img/tavs-fails.jpg (gan src, gan data-full).

KUR KO MAINĪT (viss index.html failā)
  Koncerti:  sadaļa <section class="text gigs">. Nākamajiem koncertiem
             class="gig", bijušajiem class="gig past" (oranžā krāsā).
  Video:     sadaļa <section class="videos"> – YouTube video ID.
  Skatuve:   pie "const CONFIG = {" – gaismu, uguņu, stroboskopu laiki un saites.
