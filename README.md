# *SULLA METODOLOGIA DEL PENETRATION TESTING*

## Sulla Metodologia Del Penetration Testing | Tecniche - Strumenti - Risorse

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

        - ViewDNS - one source for free DNS related tools and information.
        - DNSLookup - is an advanced DNS lookup tool.
        - DNSlytics - online DNS investigation tool.
        - DNS Spy - monitor, validate and verify your DNS configurations.
        - Zonemaster - helps you to control how your DNS works.
        - Leaf DNS - comprehensive DNS tester.
        - Find subdomains online - find subdomains for security assessment penetration test.
        - DNSdumpster - dns recon & research, find & lookup dns records.
        - DNS Table online - search for DNS records by domain, IP, CIDR, ISP.
        - intoDNS - DNS and mail server health checker.
        - DNS Bajaj - check the delegation of your domain.
        - BuddyDNS Delegation LAB - check, trace and visualize delegation of your domain.
        - dnssec-debugger - DS or DNSKEY records validator.
        - PTRarchive.com - this site is responsible for the safekeeping of historical reverse DNS records.
        - xip.io - wildcard DNS for everyone.
        - dnslookup (ceipam) - one of the best DNS propagation checker (and not only).
        - What's My DNS - DNS propagation checking tool.
        - DNSGrep - quickly searching large DNS datasets.

3. Analizzare i **BUSINESS** su cui si base l'azienda.
4. Prendere nota dal sito di ogni informazione di contatto utile: indirizzo, telefono, mail, ecc.
5. Verificare (e indagare) la presenza di eventuali **FORNITORI/PARTNER** in quanto potrebbero indirirettamente fornire ulteriori utili informazioni.
6. Ricercare su **FORUM** e simili discussioni relative all'azienda e alle persone che lavorano al suo interno.
7. Identificare la locazione geografica dell'azienda e di eventuali **uffici/sedi "satellite"**.
8. Verificare il contenuto di **precedenti versioni del sito web aziendale**, in quanto, i contenuti potrebbero essere cambiati. 
9. Verificare la presenza di **annunci di lavoro** pubblicati sui vari siti/motori di ricerca specifici dato che potrebbero indirettamente fornire informazioni sulla tipologia di prodotti hardware/software utilizzati e sull'organizzazione più in generale.
10. Effettuare una ricerca all'interno dei **Social Network (Linkedin in primis)**.
11. Cercare di ottenere una **lista del personale** che lavora all'interno dell'azienda.
12. Inviare delle **mail al personale** interno dell'azienda chiedendo "finte informazioni" al fine di acquisire ulteriori dettagli. 
13. Cercare di ottenere **dettagli personali** del personale che lavora all'interno dell'azienda.
14. Utilizzare **tool automatici** al fine di valocizzare la raccolta delle informazioni relative all'azienda.


# :boom:WEB PENETRATION TESTING 


# :boom:WIFI PENETRATION TESTING 


# :boom:CLOUD | DEVSECOPS PENETRATION TESTING 


# :boom:MOBILE PENETRATION TESTING 


# :boom:SCADA | INDUSTRIAL DEVICES PENETRATION TESTING 






