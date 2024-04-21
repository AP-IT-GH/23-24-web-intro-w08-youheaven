# 💻 08. API's uitlezen > oefening 05

## 🛠️ opdrachten

Tijdens dit labo leer je
 - gebruik maken van een API-sleutel voor toegang.

### Postman opstarten

 - Start Postman.

### authentificatie met api key

 - [API: News API](https://newsapi.org)
 - endpoint: /top-headlines

---

1. Maak een nieuw verzoek naar de API.
2. Gebruik de endpoint /top-headlines.
3. Voeg een X-Api-Key header toe met je API-sleutel.
4. Voer het verzoek uit en bekijk de respons.

{
    "status": "ok",
    "totalResults": 32,
    "articles": [
        {
            "source": {
                "id": null,
                "name": "Espn.nl"
            },
            "author": "Door de redactie",
            "title": "Ajax Vrouwen - AZ Vrouwen definitief gestaakt, keepster Liefting bewusteloos na heftige botsing - ESPN.nl",
            "description": "Grote schrik na heftige botsing AZ-keepster Femke Liefting.",
            "url": "https://www.espn.nl/voetbal/artikel/_/id/13543276/duel-tussen-vrouwen-ajax-en-az-gestaakt-keepster-liefting-weer-bij-kennis-na-zware-botsing",
            "urlToImage": "https://a2.espncdn.com/combiner/i?img=%2Fphoto%2F2024%2F0420%2Fr1321515_1296x729_16%2D9.jpg",
            "publishedAt": "2024-04-20T12:52:00Z",
            "content": "De wedstrijd tussen de vrouwen van Ajax en AZ is zaterdagmiddag na acht minuten definitief gestaakt. Keepster Femke Liefting van de Alkmaarders bleef na een botsing met aanvaller Chasity Grant roerlo… [+816 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Www.nu.nl"
            },
            "author": "NU.nl",
            "title": "Grote Oekraïense droneaanval op Rusland, brandstofdepot geraakt | Oorlog in Oekraïne - NU.nl",
            "description": null,
            "url": "https://www.nu.nl/spanningen-oekraine/6309838/grote-oekraiense-droneaanval-op-rusland-brandstofdepot-geraakt.html",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:19:00Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Telegraaf.nl"
            },
            "author": "Telegraaf.nl",
            "title": "Amalia op weg naar de troon: kroonprinses laat zich niet zomaar uit het veld slaan - Telegraaf.nl",
            "description": null,
            "url": "https://www.telegraaf.nl/nieuws/2060278986/amalia-op-weg-naar-de-troon-kroonprinses-laat-zich-niet-zomaar-uit-het-veld-slaan",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:11:54Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Www.nu.nl"
            },
            "author": "NU.nl",
            "title": "Bangalijsten gaan rond in grote Telegramgroepen, OM staat machteloos - NU.nl",
            "description": null,
            "url": "https://www.nu.nl/binnenland/6309835/bangalijsten-gaan-rond-in-grote-telegramgroepen-om-staat-machteloos.html",
            "urlToImage": null,
            "publishedAt": "2024-04-20T11:57:57Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Dvhn.nl"
            },
            "author": "DVHN Redactie",
            "title": "Demonstranten Extinction Rebellion bezetten rotonde in Eelde. 'Burgemeester Thijsen kan het krijgen zoals ie het hebben wil' - Dagblad van het Noorden",
            "description": "Een groep van circa dertig demonstranten heeft zaterdagmiddag de rotonde op het kruispunt van de Burgemeester J.G. Legroweg met de Groningerstraat in Eelde bezet.",
            "url": "https://dvhn.nl/drenthe/tynaarlo/Demonstranten-Extinction-Rebellion-bezetten-rotonde-in-Eelde-29006399.html",
            "urlToImage": "https://afbeelding.dvhn.nl/dvhn/incoming/9rwv6l-XR_Eelde%C2%A9Jaspar_Moulijn.jpg/alternates/LANDSCAPE_1920/XR_Eelde%C2%A9Jaspar_Moulijn.jpg",
            "publishedAt": "2024-04-20T11:50:39Z",
            "content": "Een groep van circa dertig demonstranten heeft zaterdagmiddag de rotonde op het kruispunt van de Burgemeester J.G. Legroweg met de Groningerstraat in Eelde bezet. Dit gebeurde kort na 12.30 uur, toen… [+1473 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Voetbalzone.nl"
            },
            "author": "Siep Engelen",
            "title": "Mikautadze doet uiterst pijnlijke onthulling over Ajax-tijd: 'Ik werd gek!' - Voetbalzone.nl",
            "description": "Georges Mikautadze heeft hard uitgehaald naar Ajax. In gesprek met <i>L’Équipe</i> vertelt hij onder andere dat hij zich totaal niet thuisvoelde in Amsterdam. De Georgische aanvaller, die inmiddels is verhuurd aan FC Metz, zat namelijk maandenlang alleen op e…",
            "url": "https://www.voetbalzone.nl/nieuws/mikautadze-doet-uiterst-pijnlijke-onthulling-over-ajax-tijd-ik-werd-gek/433750",
            "urlToImage": "https://static.voetbalzone.nl/images/photos/ori_1152_648/4435363512235.jpg",
            "publishedAt": "2024-04-20T11:42:00Z",
            "content": "Georges Mikautadze heeft hard uitgehaald naar Ajax. In gesprek met LÉquipe vertelt hij onder andere dat hij zich totaal niet thuisvoelde in Amsterdam. De Georgische aanvaller, die inmiddels is verhuu… [+1873 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Nos.nl"
            },
            "author": null,
            "title": "Koude wind houdt toeschouwers bloemencorso niet tegen - NOS",
            "description": "Een stoet vol met bloemen versierde praalwagens rijdt vandaag stapvoets de 42 kilometer lange tocht tussen Noordwijk en Haarlem.",
            "url": "https://nos.nl/l/2517476",
            "urlToImage": "https://cdn.nos.nl/image/2024/04/20/1074052/1024x576a.jpg",
            "publishedAt": "2024-04-20T11:34:38Z",
            "content": "Een bonte stoet van met bloemen versierde praalwagens is vanochtend vanuit Noordwijk naar Haarlem vertrokken.\r\nHet Bloemencorso Bollenstreek is een van de grootste corso's in Nederland en trekt volge… [+3102 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Tweakers.net"
            },
            "author": "Kevin Krikhaar",
            "title": "Thunderbird krijgt in juli ondersteuning voor Microsoft Exchange-protocol - Tweakers",
            "description": "Mozilla Thunderbird krijgt in juli native ondersteuning voor het e-mailprotocol Microsoft Exchange. Later moet er ook ondersteuning voor de agenda en het adresboek bijkomen. Het is voor het eerst dat Mozilla een nieuw protocol aan zijn e-mailclient toevoegt.",
            "url": "https://tweakers.net/nieuws/221078/thunderbird-krijgt-in-juli-ondersteuning-voor-microsoft-exchange-protocol.html",
            "urlToImage": "https://tweakers.net/i/JJEFo91hL2CKS-Wc4WkkR0kxeVQ=/134x134/filters:strip_exif()/i/2005793966.png?f=meta",
            "publishedAt": "2024-04-20T11:25:43Z",
            "content": "Mozilla Thunderbird krijgt in juli native ondersteuning voor het e-mailprotocol Microsoft Exchange. Later moet er ook ondersteuning voor de agenda en het adresboek bijkomen. Het is voor het eerst dat… [+1514 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Volkskrant.nl"
            },
            "author": "de Volkskrant",
            "title": "Amerikaans Congres stemt vandaag over steunpakketten: 'Binnen de Republikeinen is steun aan Oekraïne een enorme splijtzwam' - de Volkskrant",
            "description": null,
            "url": "https://www.volkskrant.nl/buitenland/amerikaans-congres-stemt-vandaag-over-steunpakketten-binnen-de-republikeinen-is-steun-aan-oekraine-een-enorme-splijtzwam~bdb84b09/",
            "urlToImage": null,
            "publishedAt": "2024-04-20T11:23:35Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Omroepwest.nl"
            },
            "author": null,
            "title": "Klimaatdemonstranten blokkeren kruispunt, ME haalt ze van de weg - Omroep West",
            "description": "Demonstranten van Extinction Rebellion hebben zaterdag een kruispunt in Den Haag geblokkeerd. Zo'n negentig actievoerders zaten op de Ypenburgse Stationsweg en blokkeerden het verkeer. De ME heeft het kruispunt leeggehaald.",
            "url": "https://www.omroepwest.nl/nieuws/4830638/klimaatdemonstranten-blokkeren-kruispunt-me-haalt-ze-van-de-weg",
            "urlToImage": "https://i.regiogroei.cloud/a07ea898-14b6-32c9-bbd1-62fb444d2fb6.jpg?width=1200&height=630&aspect_ratio=1200:630",
            "publishedAt": "2024-04-20T10:42:31Z",
            "content": "Vandaag, 12:31 1 minuut leestijd"
        },
        {
            "source": {
                "id": null,
                "name": "Www.ad.nl"
            },
            "author": "Gudo Tienhooven",
            "title": "Tokkies spreken voor het eerst sinds familienaam werd geruïneerd: 'Media hebben ons kapotgemaakt' - AD",
            "description": "Massa’s kijkers smulden ervan, maar alle faam bracht De Tokkies naar eigen zeggen alleen maar ellende. Een documentaire op Prime Video moet 20 jaar later voor eerherstel zorgen. We kregen een exclusief kijkje in hoe het nu gaat met de familie, die ongewild sy…",
            "url": "https://www.ad.nl/show/tokkies-spreken-voor-het-eerst-sinds-familienaam-werd-geruineerd-media-hebben-ons-kapotgemaakt~ad0a6621/",
            "urlToImage": "https://images0.persgroep.net/rcs/wNA7eHewED8kt4Ct4EWRD2Z6zHM/diocontent/242864428/_focus/0.63/0.31/_fill/1200/630/?appId=21791a8992982cd8da851550a453bd7f&quality=0.7",
            "publishedAt": "2024-04-20T09:51:00Z",
            "content": "exclusief interviewMassas kijkers smulden ervan, maar alle faam bracht De Tokkies naar eigen zeggen alleen maar ellende. Een documentaire op Prime Video moet 20 jaar later voor eerherstel zorgen. We … [+1067 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Www.nu.nl"
            },
            "author": null,
            "title": "Vorig jaar 137 Nederlandse plofkrakers opgepakt, iedereen sloeg toe in Duitsland - NU.nl",
            "description": "Vorig jaar zijn 137 Nederlanders aangehouden omdat ze vermoedelijk betrokken waren bij een plofkraak. De meeste plofkraken vonden plaats in Duitsland, meldt de politie zaterdag.",
            "url": "https://www.nu.nl/misdaad/6309823/vorig-jaar-137-nederlandse-plofkrakers-opgepakt-iedereen-sloeg-toe-in-duitsland.html",
            "urlToImage": "https://media.nu.nl/m/u1gxgacafeq7_wd1280/vorig-jaar-137-nederlandse-plofkrakers-opgepakt-iedereen-sloeg-toe-in-duitsland.jpg",
            "publishedAt": "2024-04-20T09:33:00Z",
            "content": "20 apr 2024 om 11:33 Update: 5 uur geleden \r\nVorig jaar zijn 137 Nederlanders aangehouden omdat ze vermoedelijk betrokken waren bij een plofkraak. De meeste plofkraken vonden plaats in Duitsland, mel… [+1671 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Www.nu.nl"
            },
            "author": null,
            "title": "Zogeheten 'halving' van bitcoin voltooid, beleggers hopen op prijsstijging - NU.nl",
            "description": null,
            "url": "https://www.nu.nl/economie/6309824/zogeheten-halving-van-bitcoin-voltooid-beleggers-hopen-op-prijsstijging.html",
            "urlToImage": null,
            "publishedAt": "2024-04-20T09:10:32Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Www.nu.nl"
            },
            "author": null,
            "title": "Live F1 | Reacties na superieure kwalificatie Verstappen in China - NU.nl",
            "description": "",
            "url": "https://www.nu.nl/formule-1/6309802/live-f1-reacties-na-superieure-kwalificatie-verstappen-in-china.html",
            "urlToImage": "https://media.nu.nl/m/nztxuiya611e_wd1280/live-f1-reacties-na-superieure-kwalificatie-verstappen-in-china.jpg",
            "publishedAt": "2024-04-20T08:52:00Z",
            "content": "Live F1 | Reacties na superieure kwalificatie Verstappen in China \r\n Deze inhoud kan helaas niet worden getoond Wij hebben geen toestemming voor de benodigde cookies. Aanvaard de cookies om deze inho… [+7113 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Www.ad.nl"
            },
            "author": "Marit Laurenssen/ Veronica Superguide",
            "title": "Van liefdesleven tot studie: dit wist je nog niet over de zoons van Frans en Mariska Bauer - De Gelderlander",
            "description": "Na twintig jaar wachten is de familie Bauer sinds begin april weer terug op de buis. De realityserie trekt honderdduizenden kijkers. Hoe gaat het nu eigenlijk met de vier zoons van Frans en Mariska Bauer? Een overzichtje.",
            "url": "https://www.ad.nl/show/van-liefdesleven-tot-studie-dit-wist-je-nog-niet-over-de-zoons-van-frans-en-mariska-bauer~a58f32de/",
            "urlToImage": "https://images0.persgroep.net/rcs/iSeBJIbK_Q2Rksgnuqq68MQlb9Y/diocontent/242376785/_focus/0.51/0.26/_fill/1200/630/?appId=21791a8992982cd8da851550a453bd7f&quality=0.7",
            "publishedAt": "2024-04-20T08:29:07Z",
            "content": "In De Bauers krijgen we een kijkje in het leven van Frans en Mariska Bauer en hun kinderen Christiaan (22), Jan (21), Frans Jr. (19) en Lucas (14). Inmiddels schuiven met kerst ook de vriendinnen van… [+2752 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Gelderlander.nl"
            },
            "author": null,
            "title": "Man trok deel van zijn kleding uit bij overval: nazorg voor personeel van Albert Heijn - De Gelderlander",
            "description": null,
            "url": "https://www.gelderlander.nl/nijmegen/man-trok-deel-van-zijn-kleding-uit-bij-overval-nazorg-voor-personeel-van-albert-heijn~afdf199e/",
            "urlToImage": null,
            "publishedAt": "2024-04-20T08:12:00Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Nos.nl"
            },
            "author": "NOS",
            "title": "Man die zichzelf in brand stak bij rechtbank waar Trump-zaak diende overleden - NOS",
            "description": null,
            "url": "https://nos.nl/l/2517451",
            "urlToImage": null,
            "publishedAt": "2024-04-20T07:14:44Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Parool.nl"
            },
            "author": "Jeroen Schmale",
            "title": "Vertrouwen in Máxima krijgt een knauw: bijna net zo'n lage score als Willem-Alexander - Het Parool",
            "description": "Het vertrouwen in het koningspaar is en blijft historisch laag. Vooral de cijfers van koningin Máxima krijgen een knauw. Slechts 55 procent van de Nederlanders heeft nog vertrouwen in de echtgenote van koning Willem-Alexander. Vijf jaar geleden lag dat percen…",
            "url": "https://www.parool.nl/nederland/vertrouwen-in-maxima-krijgt-een-knauw-bijna-net-zo-n-lage-score-als-willem-alexander~b64ae55b/",
            "urlToImage": "https://image.parool.nl/242874348/feature-crop/1200/630/koning-willem-alexander-en-koningin-maxima-samen-met-prinses",
            "publishedAt": "2024-04-20T06:38:30Z",
            "content": "Dat blijkt uit onderzoek onder ruim 26.000 leden van het EenVandaag Opiniepanel. Het vertrouwen in koning Willem-Alexander blijft stabiel laag: 53 procent tegen 55 vorig jaar. In prinses Amalia heeft… [+1636 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Www.ad.nl"
            },
            "author": "Sjoerd Mossou",
            "title": "Straf Vitesse klinkt vernietigend, maar stiekem werpt licentiecommissie een reddingsboei - AD",
            "description": "In zijn opinie roemt Sjoerd Mossou de strenge regels van de licentiecommissie van de KNVB. Juist die aanpak biedt Vitesse nu een reddingsboei - en beschermt het hele Nederlandse voetbal tegen luchtfietsers en durfinvesteerders.",
            "url": "https://www.ad.nl/nederlands-voetbal/straf-vitesse-klinkt-vernietigend-maar-stiekem-werpt-licentiecommissie-een-reddingsboei~a88e2352/",
            "urlToImage": "https://images0.persgroep.net/rcs/LuJ0sLew-LrjMxusvZkIj4SKeOw/diocontent/242899535/_focus/0.46/0.08/_fill/1200/630/?appId=21791a8992982cd8da851550a453bd7f&quality=0.7",
            "publishedAt": "2024-04-20T05:45:00Z",
            "content": "In zijn opinie roemt Sjoerd Mossou de strenge regels van de licentiecommissie van de KNVB. Juist die aanpak biedt Vitesse nu een reddingsboei - en beschermt het hele Nederlandse voetbal tegen luchtfi… [+27 chars]"
        },
        {
            "source": {
                "id": null,
                "name": "Rtvoost.nl"
            },
            "author": "Rutger Borgerink",
            "title": "Arriva-conducteurs over toenemende agressie in de trein: \"Dit kan zo niet langer\" - RTV Oost",
            "description": "Gescheld met kanker, met eikel, kreten als 'ga boeven vangen' en soms ook fysiek geweld: conducteurs op de trein tussen Oldenzaal en Zutphen zien de agressie onder reizigers toenemen. Vanavond staan de treinen drie minuten stil, uit protest. \"We geven een sig…",
            "url": "https://www.rtvoost.nl/nieuws/2337513/arriva-conducteurs-over-toenemende-agressie-in-de-trein-dit-kan-zo-niet-langer",
            "urlToImage": "https://i.regiogroei.cloud/c1dca1e0-c0f6-3492-849c-4ef10e984ece.jpg?width=1200&height=630&aspect_ratio=1200:630",
            "publishedAt": "2024-04-20T05:02:06Z",
            "content": null
        }
    ]
}