# Coordinated Vulnerability Disclosure (CVD)
Meldt u een kwetsbaarheid in een systeem van de Belastingdienst, Douane of Toeslagen? Doe dit dan voordat u deze met de buitenwereld deelt. Zo kunnen wij eerst maatregelen treffen. Dit heet 'Coordinated Vulnerability Disclosure' (CVD).

## Aandachtspunten melding CVD
Wij vragen u om:

- Zo snel mogelijk na ontdekking van de kwetsbaarheid deze aan ons door te geven.
- Uw bevindingen te e-mailen naar: cvd@belastingdienst.nl, cvd@douane.nl of cvd@toeslagen.nl (alleen gebruiken voor dit soort meldingen).
Versleutel de bevindingen, indien mogelijk, met onze PGP-sleutel (KeyID: 71cd8e09, Fingerprint: 06c4 83ef 1c63 93de f281 97b7 17b3 7108 71cd 8e09) om te voorkomen dat de informatie in verkeerde handen valt.
- Voldoende informatie te geven om het probleem te reproduceren zodat we dit zo snel mogelijk kunnen verhelpen.
Meestal is het IP-adres of de url van het getroffen systeem en een beschrijving van de kwetsbaarheid voldoende, maar bij complexere kwetsbaarheden kan meer informatie nodig zijn.
- Contactgegevens achter te laten zodat ons Security Operations Center met u in contact kan komen om samen te werken aan een veilig resultaat.
Laat minimaal een e-mailadres of telefoonnummer achter.
- De informatie over het beveiligingsprobleem niet met anderen te delen totdat dit is opgelost.
- Verantwoordelijk om te gaan met de kennis van het beveiligingsprobleem door geen handelingen te verrichten die verder gaan dan noodzakelijk om het beveiligingsprobleem aan te tonen.
- U te realiseren dat eventuele informatie uit onze systemen valt onder de (fiscale) geheimhoudingsplicht en dat verder bekendmaken van die informatie strafbaar is.

## Vermijd in elk geval:
- het plaatsen van malware
- het kopiëren, wijzigen of verwijderen van gegevens of configuraties van een systeem (een alternatief hiervoor is het maken van een directory listing of screenshot)
- het gebruik van het zogeheten 'bruteforcen' om toegang tot systemen te verkrijgen
- het gebruik van denial-of-service aanvallen of social engineering

## U mag het volgende van ons verwachten:
- Als uw melding aan de bovenstaande voorwaarden voldoet, verbinden wij geen juridische consequenties aan deze melding. Het Security Operations Center van de Belastingdienst behandelt uw melding strikt vertrouwelijk en deelt geen persoonlijke gegevens met derden zonder uw toestemming, tenzij dit wettelijk of uit hoofde van een rechterlijke uitspraak verplicht is.
- Wij sturen u binnen 1 werkdag een ontvangstbevestiging.
- Wij reageren binnen 5 werkdagen op uw melding met onze beoordeling van de melding en een verwachte datum voor een oplossing.
- Wij houden u van de voortgang op de hoogte. Wij lossen het door u geconstateerde beveiligingsprobleem in een systeem binnen een redelijke termijn op. In onderling overleg bepalen we wanneer en op welke wijze hierover wordt gepubliceerd.
- In onderling overleg kunnen we, als u dit wenst, uw naam vermelden als de ontdekker van de gemelde kwetsbaarheid.
- Als dank voor uw hulp bieden wij een ludieke beloning voor elke melding van een ons nog onbekend en serieus beveiligingsprobleem. De beloning zal nooit in geldelijke vorm zijn.

Deze tekst is opgesteld als aanvulling op de leidraad van het Nationaal Cyber Security Centrum (NCSC).

# Een goede melding verdient een beloning
Is de kwetsbaarheid volgens ons nog onbekend en vormt het een serieus beveiligingsprobleem? Dan krijgt u van ons een beloning (swag).

## Voorbeelden van bokaal-waardige meldingen:
- Cross-Site Scripting vulnerabilities (except self-XSS)
- SQLi and command injections
- Authentication Bypass, Unauthorized data access
- Server-Side Request Forgery
- Access to PII data
- Authentication vulnerabilities
- Directory Traversal
- Credential leaks
- Username enumeration zonder gebruik te maken van brute-force technieken

## Voorbeelden van bedankbrief-waardige meldingen:
- HTTP Host Header Injection
- CSRF
- SPF / DKIM errors

## Out-of-scope:
- Self-XSS
- Social Engineering
- Denial of Service
- Attacks on physical property of the tax authorities
- Username enumerationbrute-force technieken
- Vulnerabilities using stolen credentials
- Vulnerabilities that only apply to outdated software / browsers
- Man-in-the-middle
- Scanner outputs or scanner reports without a proof of concept showing that vulnerabilities can be exploited

Ons team controleert alle meldingen en het is mogelijk dat de uiteindelijke beloning afwijkt van de genoemde voorbeelden. Heb je een melding die hier niet tussen staat dan is die altijd welkom. Ons team zal kijken in hoeverre we de melding oppakken.

# Hall of Fame
Als u een melding doet die volgens ons een bokaal of een bedankbrief verdient, krijgt u ook een plekje in onze 'Hall of Fame'. Natuurlijk vragen we eerst of u dat wel wilt.

- Lees op 'Hall of Fame – CVD Netherlands Tax Administration' (alleen in het Engels) wie u voorgingen

# Meer informatie
Lees meer over de licentie op 'Naamsvermelding-GelijkDelen 3.0 Unported (CC BY-SA 3.0)'
