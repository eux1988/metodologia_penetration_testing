# *SULLA METODOLOGIA DEL PENETRATION TESTING*

## Sulla Metodologia Del Penetration Testing | Tecniche - Strumenti - Risorse

![PENETRATION TESTING](https://www.breachlock.com/wp-content/uploads/2019/09/V_C_3.jpg)

# :boom: NETWORK PENETRATION TESTING 

## :ballot_box_with_check: FASE 0 |  PRELIMINARE

1. Raccogliere informazioni dettagliate sull'organizzazione su cui si andrà ed effettuare l'attività di **PT (Penetration Testing)**.
2. Identificare il team IT dell'organizzazione con maggiore focus sulla parte IT Security.
3. Effettuare, se possibile, un sopralluogo FISICO nell'azienda così da raccogliere ulteriori dettagi/ punti deboli relativi al contesto in cui si andrà ad operare.
4. Discutere insieme al Cliente la **[tipologia di Penetration Testing](https://resources.infosecinstitute.com/the-types-of-penetration-testing/#gref)** che si dovrà effettuare, tra cui:

      - White | Black | Grey PT.
      - Internal | External PT.
      
5. Definita la tipologia di PT da effettuare, dettagliare quali **TEST** dovranno essere effettuati e su quali **DISPOSITIVI**.
6. Chiedere al cliente se è possibile ottenere (se presenti) precedenti **[REPORT](https://github.com/juliocesarfort/public-pentesting-reports) di PT o VULNERABILITY ASSESSMENT**.
7. Redarre insieme al cliente un **[DOCUMENTO](https://www.cms.gov/Research-Statistics-Data-and-Systems/CMS-Information-Technology/InformationSecurity/Info-Security-Library-Items/CMS-Penetration-Testing-Rules-of-Engagement-Template)** in cui sono specificati tutti gli aspetti legali relativi all'attività di PT che si andrà ad effettuare.
8. Redarre un **DOCUMENTO CONTRATTUALE** in cui sono specificati i termini economici e di durata temporale del PT.
9. Dopo aver formalizzato tutta la parte economica e contrattule, procedere con la definizione di una **LISTA DETTAGLIATA** (comprensivi di indirizzi IP, porte, servizi...) di tutti gli elementi che si dovranno testare:

      - Dispositivi di rete (Router, Switch, ecc...).
      - Server | Workstation.
      - Web Application.
      - Dispositivi SCADA | ICS.
      - Dispositivi di rete WIFI.
      - Dispositivi IoT.
      - Altro.
      
10. Essere in posseso di una **lista di contatti** lato cliente da chiamare in caso di necessità.
11. Avvertire (se previsto dalla tipologia di PT che si dovrà eseguire) l'IT TEAM del cliente quando si andranno ad effettuare le varie attività relative al PT così che possano monitore la situazione.
12. Definire come dovrà essere **REDATTO e CONSEGNATO** al cliente il **[REPORT FINALE](https://github.com/juliocesarfort/public-pentesting-reports)**.

## :ballot_box_with_check: FASE 1 |  RACCOLTA DELLE INFORMAZIONI | INFORMATION GATHERING

![OSINT LANDSCAPE](https://i.pinimg.com/originals/17/42/60/1742609b23627ea1895cb109d44e31a4.jpg)

1. Visitare il sito dell'organizzazione "target" ed effettuare l'operazione di "crawling" copiando le varie pagine localmente.
2. Effettuare una ricerca sui **DATABASE PUBBLICI** per rilevare eventuali informazioni legate al **DOMINIO** in oggetto.

      - :fire:[ViewDNS](https://viewdns.info/) - one source for free DNS related tools and information.
      - :fire:[DNSLookup](https://dnslookup.org/) - is an advanced DNS lookup tool.
      - :fire:[ DNSlytics](https://dnslytics.com/) - online DNS investigation tool.
      - :fire:[DNS Spy](https://dnsspy.io/) - monitor, validate and verify your DNS configurations.
      - :fire:[Zonemaster](https://zonemaster.iis.se/en/) - helps you to control how your DNS works.
      - :fire:[Leaf DNS](http://leafdns.com/) - comprehensive DNS tester.
      - :fire:[Find subdomains online](https://findsubdomains.com/) - find subdomains for security assessment penetration test.
      - :fire:[DNSdumpster](https://dnsdumpster.com/) - dns recon & research, find & lookup dns records.
      - :fire:[DNS Table online](https://spyse.com/) - search for DNS records by domain, IP, CIDR, ISP.
      - :fire:[intoDNS](https://intodns.com/) - DNS and mail server health checker.
      - :fire:[DNS Bajaj](http://www.zonecut.net/dns/) - check the delegation of your domain.
      - :fire:[BuddyDNS Delegation LAB](https://www.buddyns.com/delegation-lab/) - check, trace and visualize delegation of your domain.
      - :fire:[dnssec-debugger](https://dnssec-debugger.verisignlabs.com/) - DS or DNSKEY records validator.
      - :fire:[PTRarchive.com](http://ptrarchive.com/) - this site is responsible for the safekeeping of historical reverse DNS records.
      - :fire:[xip.io](http://xip.io/) - wildcard DNS for everyone.
      - :fire:[dnslookup (ceipam)](https://ceipam.eu/en/dnslookup.php) - one of the best DNS propagation checker (and not only).
      - :fire:[What's My DNS](https://www.whatsmydns.net/?utm_source=whatsmydns.com&utm_medium=redirect) - DNS propagation checking tool.
      - :fire:[DNSGrep](https://blog.erbbysam.com/index.php/2019/02/09/dnsgrep/) - quickly searching large DNS datasets.

3. Analizzare i **BUSINESS** su cui si base l'azienda.
4. Prendere nota dal sito di ogni informazione di contatto utile: indirizzo, telefono, mail, ecc.
5. Verificare (e indagare) la presenza di eventuali **FORNITORI/PARTNER** in quanto potrebbero indirirettamente fornire ulteriori utili informazioni.
6. Ricercare su **FORUM** e simili discussioni relative all'azienda e alle persone che lavorano al suo interno.
7. Identificare la locazione geografica dell'azienda e di eventuali **uffici/sedi "satellite"**.
8. Verificare il contenuto di **precedenti versioni del sito web aziendale**, in quanto, i contenuti potrebbero essere cambiati. 
9. Verificare la presenza di **annunci di lavoro** pubblicati sui vari siti/motori di ricerca specifici dato che potrebbero indirettamente fornire informazioni sulla tipologia di prodotti hardware/software utilizzati e sull'organizzazione più in generale.

      - :fire:[Linkedin](https://www.linkedin.com/)
      - :fire:[Indeed](https://it.indeed.com/)
      - :fire:[Infojobs](https://www.infojobs.it/)
      - :fire:[Monster](https://www.monster.it/)
      - :fire:[Jooble](https://it.jooble.org/)
      - :fire:[Jobsora](https://it.jobsora.com/)
      - :fire:[Almalaurea](https://www.almalaurea.it/)
      - :fire:[JobbyDoo](https://www.jobbydoo.it/)
      - :fire:[JOBRAPIDO](https://it.jobrapido.com/)
      - :fire:[CAREERJET](https://www.careerjet.it/)

10. Effettuare una ricerca all'interno dei **Social Network (Linkedin in primis)**.
11. Cercare di ottenere una **lista del personale** che lavora all'interno dell'azienda.
12. Inviare delle **mail al personale** interno dell'azienda chiedendo "finte informazioni" al fine di acquisire ulteriori dettagli. 
13. Cercare di ottenere **dettagli personali** del personale che lavora all'interno dell'azienda.
14. Utilizzare **tool automatici** al fine di valocizzare la raccolta delle informazioni relative all'azienda.
15. Utilizzare i **"MASS SCANNER"** per trovare ulteriori informazioni legate al target di riferimento.

     - :fire:[Censys](https://censys.io/)- platform that helps information security practitioners discover, monitor, and analyze devices.
     - :fire:[Shodan](https://www.shodan.io/Shodan) - the world's first search engine for Internet-connected devices.
     - :fire:[Shodan 2000](https://2000.shodan.io/#/) - do you use Shodan for everyday work? This tool looks for randomly generated data from Shodan.
     - :fire:[tableGreyNoise](https://viz.greynoise.io/) - mass scanner such as Shodan and Censys.
     - ::fire:[ZoomEye ](https://www.zoomeye.org/)- search engine for cyberspace that lets the user find specific network components.
     - :fire:[netograph](https://netograph.io/) - tools to monitor and understand deep structure of the web.
     - :fire:[FOFA](https://fofa.so/) - is a cyberspace search engine.
     - :fire:[onyphe](https://www.onyphe.io/) - is a search engine for open-source and cyber threat intelligence data collected.
     - :fire:[IntelligenceX](https://intelx.io/) - is a search engine and data archive.
     - :fire:[binaryedge](https://app.binaryedge.io/) - it scan the entire internet space and create real-time threat intelligence streams and reports.
     - :fire:[wigle ](https://wigle.net/)- is a submission-based catalog of wireless networks. All the networks. Found by Everyone.
     - :fire:[PublicWWW](https://publicwww.com/) - find any alphanumeric snippet, signature or keyword in the web pages HTML, JS and CSS code.
     - :fire:[IntelTechniques ](https://inteltechniques.com/index.html) - this repository contains hundreds of online search utilities.
     - :fire:[hunter ](https://hunter.io/)- lets you find email addresses in seconds and connect with the people that matter for your business.
     - :fire:[GhostProject?](https://ghostproject.fr/)- search by full email address or username.
     - :fire:[databreaches](https://www.databreaches.live/)  - was my email affected by data breach?
     - :fire:[We Leak Info](https://weleakinfo.com)We  - world's fastest and largest data breach search engine.
     - :fire:[Pulsedive](https://pulsedive.com/) - scans of malicious URLs, IPs, and domains, including port scans and web requests.
     - :fire:[Buckets by Grayhatwarfar](https://buckets.grayhatwarfare.com/) - database with public search for Open Amazon S3 Buckets and their contents.
     - :fire:[Vigilante.pw](https://vigilante.pw/) - the breached database directory.
     - :fire::[NerdyData ](https://nerdydata.com/)- search the web's source code for technologies, across millions of sites.
     - :fire:[maltiverse](https://www.maltiverse.com/search)  - is a service oriented to cybersecurity analysts for the advanced analysis of indicators of compromise.
     - :fire:[Leaked Source](https://leakedsource.ru/main/) - is a collaboration of data found online in the form of a lookup.
     - :fire:[pipl ](https://pipl.com/)- is the place to find the person behind the email address, social username or phone number.
     - :fire:[abuse.ch](https://abuse.ch/) - is operated by a random swiss guy fighting malware for non-profit.
     - :fire:[malc0de](http://malc0de.com/database/) - malware search engine.
     - :fire:[Cybercrime Tracker](https://cybercrime-tracker.net/index.php) - monitors and tracks various malware families that are used to perpetrate cyber crimes.
     - :fire:[searchcode](https://searchcode.com/) - helping you find real world examples of functions, API's and libraries.
     - :fire:[Insecam ](http://www.insecam.org/)- the world biggest directory of online surveillance security cameras.
     - :fire:[Rapid7 Labs Open Data](https://opendata.rapid7.com/) - is a great resources of datasets from Project Sonar.

## :ballot_box_with_check: FASE 2 |  INGEGNERIA SOCIALE | SOCIAL ENGINEERING

## :ballot_box_with_check: FASE 3 |  EXTERNAL PENETRATION TESTING

## :ballot_box_with_check: FASE 4 |  INTERNAL PENETRATION TESTING


# :boom:WEB PENETRATION TESTING 


# :boom:WIFI PENETRATION TESTING 


# :boom:CLOUD | DEVSECOPS PENETRATION TESTING 


# :boom:MOBILE PENETRATION TESTING 


# :boom:SCADA | INDUSTRIAL DEVICES PENETRATION TESTING 

# :boom:IoT PENETRATION TESTING 





