## ENUMS

### Language codes
`agencies.agency_lang`
`feed_info.default_lang`
`feed_info.feed_lang`
`translations.language`

Must be defined according to the 2 lower case letter [ISO 639-1 Code](https://www.loc.gov/standards/iso639-2/php/code_list.php), with the exception of `mul` for multilanguage

### Currency codes
`fare_attributes.currency`

Must be defined according to the 3 upper case letter active [ISO 4217 Code](https://en.wikipedia.org/wiki/ISO_4217#Active_codes)

### Timezones
`agencies.agency_timezone`
`stop_times.stop_timezone`

Must be specified according to the current [TZ database](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)

They must be in the `Region/(Zone)/City` format to take into account local daylight saving rules

*Generic* `Factory`, `Etc/*`, `GMT`, `UTC` are **not accepted**

*Deprecated* timezones are **not accepted**


### Reference
A simple list of the most common language and currency for each country, just as a reference:

CC|Language|Currency|Country
-|-|-|-
 AF | fa   | AFN      | Afghanistan
 AX | sv   | EUR      | Åland Islands
 AL | sq   | ALL      | Albania
 DZ | ar   | DZD      | Algeria
 AS | en   | USD      | American Samoa
 AD | ca   | EUR      | Andorra
 AO | pt   | AOA      | Angola
 AI | en   | XCD      | Anguilla
 AG | en   | XCD      | Antigua and Barbuda
 AR | es   | ARS      | Argentina
 AM | hy   | AMD      | Armenia
 AW | nl   | AWG      | Aruba
 AU | en   | AUD      | Australia
 AT | de   | EUR      | Austria
 AZ | az   | AZN      | Azerbaijan
 BS | en   | BSD      | Bahamas
 BH | ar   | BHD      | Bahrain
 BD | bn   | BDT      | Bangladesh
 BB | en   | BBD      | Barbados
 BY | be   | BYN      | Belarus
 BE | nl   | EUR      | Belgium
 BZ | en   | BZD      | Belize
 BJ | fr   | XOF      | Benin
 BM | en   | BMD      | Bermuda
 BT | dz   | BTN      | Bhutan
 BO | es   | BOB      | Bolivia
 BQ | nl   | USD      | Bonaire
 BA | bs   | BAM      | Bosnia and Herzegovina
 BW | en   | BWP      | Botswana
 BR | pt   | BRL      | Brazil
 IO | en   | USD      | British Indian Ocean Territory
 BN | ms   | BND      | Brunei Darussalam
 BG | bg   | BGN      | Bulgaria
 BF | fr   | XOF      | Burkina Faso
 BI | fr   | BIF      | Burundi
 CV | pt   | CVE      | Cabo Verde
 KH | km   | KHR      | Cambodia
 CM | en   | XAF      | Cameroon
 CA | en   | CAD      | Canada
 KY | en   | KYD      | Cayman Islands
 CF | fr   | XAF      | Central African Republic
 TD | fr   | XAF      | Chad
 CL | es   | CLP      | Chile
 CN | zh   | CNY      | China
 CX | en   | AUD      | Christmas Island
 CC | ms   | AUD      | Cocos Islands
 CO | es   | COP      | Colombia
 KM | ar   | KMF      | Comoros
 CK | en   | NZD      | Cook Islands
 CR | es   | CRC      | Costa Rica
 HR | hr   | HRK      | Croatia
 CU | es   | CUP      | Cuba
 CW | nl   | ANG      | Curaçao
 CY | el   | EUR      | Cyprus
 CZ | cs   | CZK      | Czechia
 CD | fr   | CDF      | Democratic Republic of the Congo
 DK | da   | DKK      | Denmark
 DJ | fr   | DJF      | Djibouti
 DM | en   | XCD      | Dominica
 DO | es   | DOP      | Dominican Republic
 EC | es   | USD      | Ecuador
 EG | ar   | EGP      | Egypt
 SV | es   | USD      | El Salvador
 GQ | es   | XAF      | Equatorial Guinea
 ER | aa   | ERN      | Eritrea
 EE | et   | EUR      | Estonia
 SZ | en   | SZL      | Eswatini
 ET | am   | ETB      | Ethiopia
 FK | en   | FKP      | Falkland Islands (Malvinas)
 FO | fo   | DKK      | Faroe Islands
 FJ | en   | FJD      | Fiji
 FI | fi   | EUR      | Finland
 FR | fr   | EUR      | France
 GF | fr   | EUR      | French Guiana
 PF | fr   | XPF      | French Polynesia
 TF | fr   | EUR      | French Southern Territories
 GA | fr   | XAF      | Gabon
 GM | en   | GMD      | Gambia
 GE | ka   | GEL      | Georgia
 DE | de   | EUR      | Germany
 GH | en   | GHS      | Ghana
 GI | en   | GIP      | Gibraltar
 GR | el   | EUR      | Greece
 GL | kl   | DKK      | Greenland
 GD | en   | XCD      | Grenada
 GP | fr   | EUR      | Guadeloupe
 GU | en   | USD      | Guam
 GT | es   | GTQ      | Guatemala
 GG | en   | GBP      | Guernsey
 GN | fr   | GNF      | Guinea
 GW | pt   | XOF      | Guinea-Bissau
 GY | en   | GYD      | Guyana
 HT | ht   | HTG      | Haiti
 VA | la   | EUR      | Holy See
 HN | es   | HNL      | Honduras
 HK | zh   | HKD      | Hong Kong
 HU | hu   | HUF      | Hungary
 IS | is   | ISK      | Iceland
 IN | en   | INR      | India
 ID | id   | IDR      | Indonesia
 IR | fa   | IRR      | Iran
 IQ | ar   | IQD      | Iraq
 IE | en   | EUR      | Ireland
 IM | en   | GBP      | Isle of Man
 IL | he   | ILS      | Israel
 IT | it   | EUR      | Italy
 CI | fr   | XOF      | Ivory Coast
 JM | en   | JMD      | Jamaica
 JP | ja   | JPY      | Japan
 JE | en   | GBP      | Jersey
 JO | ar   | JOD      | Jordan
 KZ | kk   | KZT      | Kazakhstan
 KE | en   | KES      | Kenya
 KI | en   | AUD      | Kiribati
 XK | sq   | EUR      | Kosovo
 KW | ar   | KWD      | Kuwait
 KG | ky   | KGS      | Kyrgyzstan
 LA | lo   | LAK      | Laos
 LV | lv   | EUR      | Latvia
 LB | ar   | LBP      | Lebanon
 LS | en   | LSL      | Lesotho
 LR | en   | LRD      | Liberia
 LY | ar   | LYD      | Libya
 LI | de   | CHF      | Liechtenstein
 LT | lt   | EUR      | Lithuania
 LU | lb   | EUR      | Luxembourg
 MO | zh   | MOP      | Macao
 MG | fr   | MGA      | Madagascar
 MW | ny   | MWK      | Malawi
 MY | ms   | MYR      | Malaysia
 MV | dv   | MVR      | Maldives
 ML | fr   | XOF      | Mali
 MT | mt   | EUR      | Malta
 MH | mh   | USD      | Marshall Islands
 MQ | fr   | EUR      | Martinique
 MR | ar   | MRU      | Mauritania
 MU | en   | MUR      | Mauritius
 YT | fr   | EUR      | Mayotte
 MX | es   | MXN      | Mexico
 FM | en   | USD      | Micronesia
 MD | ro   | MDL      | Moldova
 MC | fr   | EUR      | Monaco
 MN | mn   | MNT      | Mongolia
 ME | sr   | EUR      | Montenegro
 MS | en   | XCD      | Montserrat
 MA | ar   | MAD      | Morocco
 MZ | pt   | MZN      | Mozambique
 MM | my   | MMK      | Myanmar
 NA | en   | NAD      | Namibia
 NR | na   | AUD      | Nauru
 NP | ne   | NPR      | Nepal
 NL | nl   | EUR      | Netherlands
 NC | fr   | XPF      | New Caledonia
 NZ | en   | NZD      | New Zealand
 NI | es   | NIO      | Nicaragua
 NE | fr   | XOF      | Niger
 NG | en   | NGN      | Nigeria
 NU | en   | NZD      | Niue
 NF | en   | AUD      | Norfolk Island
 MP | tl   | USD      | Northern Mariana Islands
 KP | ko   | KPW      | North Korea
 MK | mk   | MKD      | North Macedonia
 NO | no   | NOK      | Norway
 OM | ar   | OMR      | Oman
 PK | ur   | PKR      | Pakistan
 PW | en   | USD      | Palau
 PS | ar   | ILS      | Palestine
 PA | es   | PAB      | Panama
 PG | en   | PGK      | Papua New Guinea
 PY | es   | PYG      | Paraguay
 PE | es   | PEN      | Peru
 PH | tl   | PHP      | Philippines
 PN | en   | NZD      | Pitcairn
 PL | pl   | PLN      | Poland
 PT | pt   | EUR      | Portugal
 PR | en   | USD      | Puerto Rico
 QA | ar   | QAR      | Qatar
 CG | fr   | XAF      | Republic of the Congo
 RE | fr   | EUR      | Réunion
 RO | ro   | RON      | Romania
 RU | ru   | RUB      | Russia
 RW | rw   | RWF      | Rwanda
 BL | fr   | EUR      | Saint Barthélemy
 SH | en   | SHP      | Saint Helena
 KN | en   | XCD      | Saint Kitts and Nevis
 LC | en   | XCD      | Saint Lucia
 MF | fr   | EUR      | Saint Martin
 PM | fr   | EUR      | Saint Pierre and Miquelon
 VC | en   | XCD      | Saint Vincent and the Grenadines
 WS | sm   | WST      | Samoa
 SM | it   | EUR      | San Marino
 ST | pt   | STN      | Sao Tome and Principe
 SA | ar   | SAR      | Saudi Arabia
 SN | fr   | XOF      | Senegal
 RS | sr   | RSD      | Serbia
 SC | en   | SCR      | Seychelles
 SL | en   | SLL      | Sierra Leone
 SG | en   | SGD      | Singapore
 SX | nl   | ANG      | Sint Maarten
 SK | sk   | EUR      | Slovakia
 SI | sl   | EUR      | Slovenia
 SB | en   | SBD      | Solomon Islands
 SO | so   | SOS      | Somalia
 ZA | zu   | ZAR      | South Africa
 GS | en   | GBP      | South Georgia and the South Sandwich Islands
 KR | ko   | KRW      | South Korea
 SS | en   | SSP      | South Sudan
 ES | es   | EUR      | Spain
 LK | si   | LKR      | Sri Lanka
 SD | ar   | SDG      | Sudan
 SR | nl   | SRD      | Suriname
 SJ | no   | NOK      | Svalbard and Jan Mayen
 SE | sv   | SEK      | Sweden
 CH | de   | CHF      | Switzerland
 SY | ar   | SYP      | Syrian Arab Republic
 TW | zh   | TWD      | Taiwan
 TJ | tg   | TJS      | Tajikistan
 TZ | sw   | TZS      | Tanzania
 TH | th   | THB      | Thailand
 TL | pt   | USD      | Timor-Leste
 TG | fr   | XOF      | Togo
 TK | en   | NZD      | Tokelau
 TO | to   | TOP      | Tonga
 TT | en   | TTD      | Trinidad and Tobago
 TN | ar   | TND      | Tunisia
 TR | tr   | TRY      | Turkey
 TM | tk   | TMT      | Turkmenistan
 TC | en   | USD      | Turks and Caicos Islands
 TV | en   | AUD      | Tuvalu
 UG | en   | UGX      | Uganda
 UA | uk   | UAH      | Ukraine
 AE | ar   | AED      | United Arab Emirates
 GB | en   | GBP      | United Kingdom
 UM | en   | USD      | United States Minor Outlying Islands
 US | en   | USD      | United States of America
 UY | es   | UYU      | Uruguay
 UZ | uz   | UZS      | Uzbekistan
 VU | bi   | VUV      | Vanuatu
 VE | es   | VES      | Venezuela
 VN | vi   | VND      | Viet Nam
 VG | en   | USD      | Virgin Islands (British)
 VI | en   | USD      | Virgin Islands (US)
 WF | fr   | XPF      | Wallis and Futuna
 EH | ar   | MAD      | Western Sahara
 YE | ar   | YER      | Yemen
 ZM | en   | ZMW      | Zambia
 ZW | en   | ZWL      | Zimbabwe

And the relation between timezones and countries:

CC|Timezone
-|-
 CI         | Africa/Abidjan
 GH         | Africa/Accra
 ET         | Africa/Addis_Ababa
 DZ         | Africa/Algiers
 ER         | Africa/Asmara
 ML         | Africa/Bamako
 CF         | Africa/Bangui
 GM         | Africa/Banjul
 GW         | Africa/Bissau
 MW         | Africa/Blantyre
 CG         | Africa/Brazzaville
 BI         | Africa/Bujumbura
 EG         | Africa/Cairo
 MA         | Africa/Casablanca
 ES         | Africa/Ceuta
 GN         | Africa/Conakry
 SN         | Africa/Dakar
 TZ         | Africa/Dar_es_Salaam
 DJ         | Africa/Djibouti
 CM         | Africa/Douala
 EH         | Africa/El_Aaiun
 SL         | Africa/Freetown
 BW         | Africa/Gaborone
 ZW         | Africa/Harare
 ZA         | Africa/Johannesburg
 SS         | Africa/Juba
 UG         | Africa/Kampala
 SD         | Africa/Khartoum
 RW         | Africa/Kigali
 CD         | Africa/Kinshasa
 NG         | Africa/Lagos
 GA         | Africa/Libreville
 TG         | Africa/Lome
 AO         | Africa/Luanda
 CD         | Africa/Lubumbashi
 ZM         | Africa/Lusaka
 GQ         | Africa/Malabo
 MZ         | Africa/Maputo
 LS         | Africa/Maseru
 SZ         | Africa/Mbabane
 SO         | Africa/Mogadishu
 LR         | Africa/Monrovia
 KE         | Africa/Nairobi
 TD         | Africa/Ndjamena
 NE         | Africa/Niamey
 MR         | Africa/Nouakchott
 BF         | Africa/Ouagadougou
 BJ         | Africa/Porto-Novo
 ST         | Africa/Sao_Tome
 LY         | Africa/Tripoli
 TN         | Africa/Tunis
 NA         | Africa/Windhoek
 US         | America/Adak
 US         | America/Anchorage
 AI         | America/Anguilla
 AG         | America/Antigua
 BR         | America/Araguaina
 AR         | America/Argentina/Buenos_Aires
 AR         | America/Argentina/Catamarca
 AR         | America/Argentina/Cordoba
 AR         | America/Argentina/Jujuy
 AR         | America/Argentina/La_Rioja
 AR         | America/Argentina/Mendoza
 AR         | America/Argentina/Rio_Gallegos
 AR         | America/Argentina/Salta
 AR         | America/Argentina/San_Juan
 AR         | America/Argentina/San_Luis
 AR         | America/Argentina/Tucuman
 AR         | America/Argentina/Ushuaia
 AW         | America/Aruba
 PY         | America/Asuncion
 CA         | America/Atikokan
 BR         | America/Bahia
 MX         | America/Bahia_Banderas
 BB         | America/Barbados
 BR         | America/Belem
 BZ         | America/Belize
 CA         | America/Blanc-Sablon
 BR         | America/Boa_Vista
 CO         | America/Bogota
 US         | America/Boise
 CA         | America/Cambridge_Bay
 BR         | America/Campo_Grande
 MX         | America/Cancun
 VE         | America/Caracas
 GF         | America/Cayenne
 KY         | America/Cayman
 US         | America/Chicago
 MX         | America/Chihuahua
 CR         | America/Costa_Rica
 CA         | America/Creston
 BR         | America/Cuiaba
 CW         | America/Curacao
 GL         | America/Danmarkshavn
 CA         | America/Dawson
 CA         | America/Dawson_Creek
 US         | America/Denver
 US         | America/Detroit
 DM         | America/Dominica
 CA         | America/Edmonton
 BR         | America/Eirunepe
 SV         | America/El_Salvador
 CA         | America/Fort_Nelson
 BR         | America/Fortaleza
 CA         | America/Glace_Bay
 CA         | America/Goose_Bay
 TC         | America/Grand_Turk
 GD         | America/Grenada
 GP         | America/Guadeloupe
 GT         | America/Guatemala
 EC         | America/Guayaquil
 GY         | America/Guyana
 CA         | America/Halifax
 CU         | America/Havana
 MX         | America/Hermosillo
 US         | America/Indiana/Indianapolis
 US         | America/Indiana/Knox
 US         | America/Indiana/Marengo
 US         | America/Indiana/Petersburg
 US         | America/Indiana/Tell_City
 US         | America/Indiana/Vevay
 US         | America/Indiana/Vincennes
 US         | America/Indiana/Winamac
 CA         | America/Inuvik
 CA         | America/Iqaluit
 JM         | America/Jamaica
 US         | America/Juneau
 US         | America/Kentucky/Louisville
 US         | America/Kentucky/Monticello
 BQ         | America/Kralendijk
 BO         | America/La_Paz
 PE         | America/Lima
 US         | America/Los_Angeles
 SX         | America/Lower_Princes
 BR         | America/Maceio
 NI         | America/Managua
 BR         | America/Manaus
 MF         | America/Marigot
 MQ         | America/Martinique
 MX         | America/Matamoros
 MX         | America/Mazatlan
 US         | America/Menominee
 MX         | America/Merida
 US         | America/Metlakatla
 MX         | America/Mexico_City
 PM         | America/Miquelon
 CA         | America/Moncton
 MX         | America/Monterrey
 UY         | America/Montevideo
 MS         | America/Montserrat
 BS         | America/Nassau
 US         | America/New_York
 CA         | America/Nipigon
 US         | America/Nome
 BR         | America/Noronha
 US         | America/North_Dakota/Beulah
 US         | America/North_Dakota/Center
 US         | America/North_Dakota/New_Salem
 GL         | America/Nuuk
 MX         | America/Ojinaga
 PA         | America/Panama
 CA         | America/Pangnirtung
 SR         | America/Paramaribo
 US         | America/Phoenix
 TT         | America/Port_of_Spain
 HT         | America/Port-au-Prince
 BR         | America/Porto_Velho
 PR         | America/Puerto_Rico
 CL         | America/Punta_Arenas
 CA         | America/Rainy_River
 CA         | America/Rankin_Inlet
 BR         | America/Recife
 CA         | America/Regina
 CA         | America/Resolute
 BR         | America/Rio_Branco
 BR         | America/Santarem
 CL         | America/Santiago
 DO         | America/Santo_Domingo
 BR         | America/Sao_Paulo
 GL         | America/Scoresbysund
 US         | America/Sitka
 BL         | America/St_Barthelemy
 CA         | America/St_Johns
 KN         | America/St_Kitts
 LC         | America/St_Lucia
 VI         | America/St_Thomas
 VC         | America/St_Vincent
 CA         | America/Swift_Current
 HN         | America/Tegucigalpa
 GL         | America/Thule
 CA         | America/Thunder_Bay
 MX         | America/Tijuana
 CA         | America/Toronto
 VG         | America/Tortola
 CA         | America/Vancouver
 CA         | America/Whitehorse
 CA         | America/Winnipeg
 US         | America/Yakutat
 CA         | America/Yellowknife
 SJ         | Arctic/Longyearbyen
 YE         | Asia/Aden
 KZ         | Asia/Almaty
 JO         | Asia/Amman
 RU         | Asia/Anadyr
 KZ         | Asia/Aqtau
 KZ         | Asia/Aqtobe
 TM         | Asia/Ashgabat
 KZ         | Asia/Atyrau
 IQ         | Asia/Baghdad
 BH         | Asia/Bahrain
 AZ         | Asia/Baku
 TH         | Asia/Bangkok
 RU         | Asia/Barnaul
 LB         | Asia/Beirut
 KG         | Asia/Bishkek
 BN         | Asia/Brunei
 RU         | Asia/Chita
 MN         | Asia/Choibalsan
 LK         | Asia/Colombo
 SY         | Asia/Damascus
 BD         | Asia/Dhaka
 TL         | Asia/Dili
 AE         | Asia/Dubai
 TJ         | Asia/Dushanbe
 CY         | Asia/Famagusta
 PS         | Asia/Gaza
 PS         | Asia/Hebron
 VN         | Asia/Ho_Chi_Minh
 HK         | Asia/Hong_Kong
 MN         | Asia/Hovd
 RU         | Asia/Irkutsk
 TR         | Asia/Istanbul
 ID         | Asia/Jakarta
 ID         | Asia/Jayapura
 IL         | Asia/Jerusalem
 AF         | Asia/Kabul
 RU         | Asia/Kamchatka
 PK         | Asia/Karachi
 NP         | Asia/Kathmandu
 RU         | Asia/Khandyga
 IN         | Asia/Kolkata
 RU         | Asia/Krasnoyarsk
 MY         | Asia/Kuala_Lumpur
 MY         | Asia/Kuching
 KW         | Asia/Kuwait
 MO         | Asia/Macau
 RU         | Asia/Magadan
 ID         | Asia/Makassar
 PH         | Asia/Manila
 OM         | Asia/Muscat
 CY         | Asia/Nicosia
 RU         | Asia/Novokuznetsk
 RU         | Asia/Novosibirsk
 RU         | Asia/Omsk
 KZ         | Asia/Oral
 KH         | Asia/Phnom_Penh
 ID         | Asia/Pontianak
 KP         | Asia/Pyongyang
 QA         | Asia/Qatar
 KZ         | Asia/Qostanay
 KZ         | Asia/Qyzylorda
 SA         | Asia/Riyadh
 RU         | Asia/Sakhalin
 UZ         | Asia/Samarkand
 KR         | Asia/Seoul
 CN         | Asia/Shanghai
 SG         | Asia/Singapore
 RU         | Asia/Srednekolymsk
 TW         | Asia/Taipei
 UZ         | Asia/Tashkent
 GE         | Asia/Tbilisi
 IR         | Asia/Tehran
 BT         | Asia/Thimphu
 JP         | Asia/Tokyo
 RU         | Asia/Tomsk
 MN         | Asia/Ulaanbaatar
 CN         | Asia/Urumqi
 RU         | Asia/Ust-Nera
 LA         | Asia/Vientiane
 RU         | Asia/Vladivostok
 RU         | Asia/Yakutsk
 MM         | Asia/Yangon
 RU         | Asia/Yekaterinburg
 AM         | Asia/Yerevan
 PT         | Atlantic/Azores
 BM         | Atlantic/Bermuda
 ES         | Atlantic/Canary
 CV         | Atlantic/Cape_Verde
 FO         | Atlantic/Faroe
 PT         | Atlantic/Madeira
 IS         | Atlantic/Reykjavik
 GS         | Atlantic/South_Georgia
 SH         | Atlantic/St_Helena
 FK         | Atlantic/Stanley
 AU         | Australia/Adelaide
 AU         | Australia/Brisbane
 AU         | Australia/Broken_Hill
 AU         | Australia/Darwin
 AU         | Australia/Eucla
 AU         | Australia/Hobart
 AU         | Australia/Lindeman
 AU         | Australia/Lord_Howe
 AU         | Australia/Melbourne
 AU         | Australia/Perth
 AU         | Australia/Sydney
 NL         | Europe/Amsterdam
 AD         | Europe/Andorra
 RU         | Europe/Astrakhan
 GR         | Europe/Athens
 RS         | Europe/Belgrade
 DE         | Europe/Berlin
 SK         | Europe/Bratislava
 BE         | Europe/Brussels
 RO         | Europe/Bucharest
 HU         | Europe/Budapest
 DE         | Europe/Busingen
 MD         | Europe/Chisinau
 DK         | Europe/Copenhagen
 IE         | Europe/Dublin
 GI         | Europe/Gibraltar
 GG         | Europe/Guernsey
 FI         | Europe/Helsinki
 IM         | Europe/Isle_of_Man
 TR         | Europe/Istanbul
 JE         | Europe/Jersey
 RU         | Europe/Kaliningrad
 UA         | Europe/Kiev
 RU         | Europe/Kirov
 PT         | Europe/Lisbon
 SI         | Europe/Ljubljana
 GB         | Europe/London
 LU         | Europe/Luxembourg
 ES         | Europe/Madrid
 MT         | Europe/Malta
 AX         | Europe/Mariehamn
 BY         | Europe/Minsk
 MC         | Europe/Monaco
 RU         | Europe/Moscow
 CY         | Europe/Nicosia
 NO         | Europe/Oslo
 FR         | Europe/Paris
 ME         | Europe/Podgorica
 CZ         | Europe/Prague
 LV         | Europe/Riga
 IT         | Europe/Rome
 RU         | Europe/Samara
 SM         | Europe/San_Marino
 BA         | Europe/Sarajevo
 RU         | Europe/Saratov
 UA         | Europe/Simferopol
 MK         | Europe/Skopje
 BG         | Europe/Sofia
 SE         | Europe/Stockholm
 EE         | Europe/Tallinn
 AL         | Europe/Tirane
 RU         | Europe/Ulyanovsk
 UA         | Europe/Uzhgorod
 LI         | Europe/Vaduz
 VA         | Europe/Vatican
 AT         | Europe/Vienna
 LT         | Europe/Vilnius
 RU         | Europe/Volgograd
 PL         | Europe/Warsaw
 HR         | Europe/Zagreb
 UA         | Europe/Zaporozhye
 CH         | Europe/Zurich
 MG         | Indian/Antananarivo
 IO         | Indian/Chagos
 CX         | Indian/Christmas
 CC         | Indian/Cocos
 KM         | Indian/Comoro
 TF         | Indian/Kerguelen
 SC         | Indian/Mahe
 MV         | Indian/Maldives
 MU         | Indian/Mauritius
 YT         | Indian/Mayotte
 RE         | Indian/Reunion
 WS         | Pacific/Apia
 NZ         | Pacific/Auckland
 PG         | Pacific/Bougainville
 NZ         | Pacific/Chatham
 FM         | Pacific/Chuuk
 CL         | Pacific/Easter
 VU         | Pacific/Efate
 KI         | Pacific/Enderbury
 TK         | Pacific/Fakaofo
 FJ         | Pacific/Fiji
 TV         | Pacific/Funafuti
 EC         | Pacific/Galapagos
 PF         | Pacific/Gambier
 SB         | Pacific/Guadalcanal
 GU         | Pacific/Guam
 US         | Pacific/Honolulu
 KI         | Pacific/Kiritimati
 FM         | Pacific/Kosrae
 MH         | Pacific/Kwajalein
 MH         | Pacific/Majuro
 PF         | Pacific/Marquesas
 UM         | Pacific/Midway
 NR         | Pacific/Nauru
 NU         | Pacific/Niue
 NF         | Pacific/Norfolk
 NC         | Pacific/Noumea
 AS         | Pacific/Pago_Pago
 PW         | Pacific/Palau
 PN         | Pacific/Pitcairn
 FM         | Pacific/Pohnpei
 PG         | Pacific/Port_Moresby
 CK         | Pacific/Rarotonga
 MP         | Pacific/Saipan
 PF         | Pacific/Tahiti
 KI         | Pacific/Tarawa
 TO         | Pacific/Tongatapu
 UM         | Pacific/Wake
 WF         | Pacific/Wallis


If you cannot find your timezone, please browse the [TZ database](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) table, it may be *deprecated*.
