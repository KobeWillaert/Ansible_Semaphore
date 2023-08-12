# Ansible_Semaphore
Ansible SemaphoreLinks to an external site. is een UI voor Ansible. Met Semaphore kan je Ansible playbooks runnen, de output bekijken en als team samenwerken.
In deze opdracht ga je zelf een Semaphore server installeren en configureren.

Je maakt een verslag (1 PDF) van je activiteiten en geeft een live demonstratie van de werking op 23 augustus (datums onder voorbehoud - check het lesrooster!). Je contacteert de lector zelf voor een afspraak aan het begin van de examenperiode in de week van 15 augustus.

Ontwikkel je role(s) op Github classroomLinks to an external site..

Upload ook alle nodige bestanden hier op LEHO en voeg 1 asciinema cast file toe met daarin een zichtbare run van je playbook. Zorg dat je de live demonstratie op je laptop kan geven.
De Ansible bestanden mogen gecomprimeerd geüpload worden. Andere (PDF, asciinema) niet.

Vereisten
Stop niet bij de installatie. Er dient ook een configuratie te gebeuren. Dat wil zeggen dat je accounts en connecties dient toe te voegen.
Geen docker! Je voert een normale installatie uit (dus: package installeren, database koppelen, reverse proxy,...)
Maak gebruik van 1 of meerdere roles. Gebruik logica bij het bepalen wat in je role, en wat in je play gaat. Ook onderstaande vereisten hoeven niet noodzakelijk allemaal in hetzelfde playbook.
Voeg minstens 2 verschillende projects toe. (Het onderwerp mag je verzinnen)
Voeg minimum 4 accounts toe. Uiteraard doe je dat automatisch (bijvoorbeeld vanuit een .CSV file)
Verdeel de accounts onder de projecten, er is telkens minstens 1 admin.
Voeg een key "None" toe met als type "None".
Voeg een (eigen) repository toe met daarin een Ansible playbook. Dat mag een eenvoudig playbook zijn, zoals een playbook om apt update uit te voeren.
Voorzie een backup methode.
Hou rekening met de veiligheid (HTTPS via ACME bijvoorbeeld)
Gebruik hostnames waar mogelijk.
Gebruik git. Hou daarbij rekening met andere gebruikers. Wat je op git plaatst is je code en uitleg (README.md). Geen asciinema file, tenzij dat een meerwaarde is voor je uitleg.
Als je extra zaken kan bedenken die te automatiseren vallen mag dat zeker. (voorbeeld: semaphore's bash completion)

Tips
Voorzie voldoende tijd! Dit is geen kleine opdracht.
Lees de documentatie, en eventueel zelfs de code. Er zijn voorbeelden te vinden op https://github.com/ansible-semaphore/semaphoreLinks to an external site. (zoals een nginx configuratie).
Zorg voor een logische structuur in je verslag. Maak het professioneel (niet: "ik deed x en vervolgens deed ik y", maar een inleiding, uitgewerkte onderdelen, voldoende uitleg en leesbare screenshots of codeblokken.) Vergeet niet uit te leggen "wat, waarom en hoe". Gebruik enkel screenshots waar dat een meerwaarde is. (Geen screenshots van 'next' knoppen of van een apt install commando.)
Je verslag moet zowel een verloop van je eigen ervaringen zijn (zoals een blog) als een handleiding waar een andere technisch onderlegde persoon mee aan de slag kan.
Dit leent zich uitstekend tot het toevoegen van procedures (toevoegen van een account, rollback, backup,..)
Geef aandacht aan de code blokken in je verslag (monotype, YAML layout)
Let op voor plagiaat. Gebruik bronvermelding waar nodig en zorg dat je de code begrijpt. (Ontwerp het zelf)
Vergeet niet om variabelen en conditionals te gebruiken waar dat handig is (vaak!)
Je kan de database structuur leren kennen door wijzigingen via de web interface door te voeren. Zo kan je achterhalen welke informatie er in je queries hoort en welke tabellen/kolommen je dient aan te passen.
Backup, of beter (gedocumenteerde backups)
Structureer je git repository op een manier dat deze na een git clone op redelijke wijze bruikbaar is. Beschrijf het gebruik in je README.md.
Semaphore heeft een configuratiefile nodig. Je kan die maken met Ansible, of de Ansible expect module gebruiken om de wizard te doorlopen.
