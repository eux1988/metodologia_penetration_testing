# *SULLA METODOLOGIA DEL PENETRATION TESTING*

## Sulla Metodologia Del Penetration Testing | Tecniche - Strumenti - Risorse

![PENETRATION TESTING](https://www.breachlock.com/wp-content/uploads/2019/09/V_C_3.jpg)

# :boom: NETWORK PENETRATION TESTING 

## :ballot_box_with_check: FASE 0 | PRELIMINARE

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

      - :fire:Dispositivi di rete (Router, Switch, ecc...).
      - :fire:Server | Workstation.
      - :fire:Web Application.
      - :fire:Dispositivi SCADA | ICS.
      - :fire:Dispositivi di rete WIFI.
      - :fire:Dispositivi IoT.
      - :fire:Altro.
      
10. Essere in posseso di una **lista di contatti** lato cliente da chiamare in caso di necessità.
11. Avvertire (se previsto dalla tipologia di PT che si dovrà eseguire) l'IT TEAM del cliente quando si andranno ad effettuare le varie attività relative al PT così che possano monitore la situazione.
12. Definire come dovrà essere **REDATTO e CONSEGNATO** al cliente il **[REPORT FINALE](https://github.com/juliocesarfort/public-pentesting-reports)**.

## :ballot_box_with_check: FASE 1 | RACCOLTA DELLE INFORMAZIONI | INFORMATION GATHERING

![OSINT LANDSCAPE](https://i.pinimg.com/originals/17/42/60/1742609b23627ea1895cb109d44e31a4.jpg)

### :bomb: DI SEGUITO UN'OTTIMA LISTA DI TOOL OSINT -> [Awesome OSINT](https://github.com/jivoi/awesome-osint)

1. Visitare il sito dell'organizzazione "target" ed effettuare l'operazione di "crawling" copiando le varie pagine localmente.
2. Effettuare una ricerca sui **DATABASE PUBBLICI** per rilevare eventuali informazioni legate al **DOMINIO** in oggetto.
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
     
## :ballot_box_with_check: FASE 2 | INGEGNERIA SOCIALE | SOCIAL ENGINEERING

:pill:L'azione di INGEGNERIA SOCIALE si può idealmente collocare vicino alla fase di INFORMATION GATHERING in quanto ci permette di ottenere INFORMAZIONI di valore per le successive fasi del PT.

### :eight_spoked_asterisk: IMPERSONATION

### :eight_spoked_asterisk: EAVESDROPPING

### :eight_spoked_asterisk: SHOULDER SURFING

### :eight_spoked_asterisk: DUMPSTER DIVING

### :eight_spoked_asterisk: REVERSE SOCIAL ENGINEERING

### :eight_spoked_asterisk: PIGGYBACKING 

### :eight_spoked_asterisk: TAILGATING

### :eight_spoked_asterisk: PHISHING

### :eight_spoked_asterisk: SPEAR PHISHING

### :eight_spoked_asterisk: PUBLISHING MALICIOUS APPS

### :eight_spoked_asterisk: REPACKAGING LEGITIMATE APPS

### :eight_spoked_asterisk: FAKE SECURITY APPS

## :ballot_box_with_check: FASE 3 | EXTERNAL PENETRATION TESTING

### :eight_spoked_asterisk: VULNERABILITY ASSESSMENT
#### :eight_pointed_black_star: MISCONFIGURATION
#### :eight_pointed_black_star: DEFAULT INSTALLATIONS
#### :eight_pointed_black_star: BUFFER OVERFLOWS
#### :eight_pointed_black_star: UNPATCHED SERVERS
#### :eight_pointed_black_star: DESIGN FLAWS
#### :eight_pointed_black_star: OPERATING SYSTEM FLAWS
#### :eight_pointed_black_star: APPLICATION FLAWS
#### :eight_pointed_black_star: OPEN SERVICES
#### :eight_pointed_black_star: DEFAULT PASSWORDS



### :eight_spoked_asterisk: COMMON NETWORK SERVICES ASSESSMENT

#### :eight_pointed_black_star: FTP
#### :eight_pointed_black_star: TFTP
#### :eight_pointed_black_star: SSH
#### :eight_pointed_black_star: TELNET
#### :eight_pointed_black_star: IPMI
#### :eight_pointed_black_star: DNS
#### :eight_pointed_black_star: DHCP
#### :eight_pointed_black_star: ARP
#### :eight_pointed_black_star: NTP
#### :eight_pointed_black_star: SNMP
#### :eight_pointed_black_star: SMTP
#### :eight_pointed_black_star: LDAP
#### :eight_pointed_black_star: KERBEROS
#### :eight_pointed_black_star: VNC
#### :eight_pointed_black_star: Unix RPC
#### :eight_pointed_black_star: NetBIOS
#### :eight_pointed_black_star: SMB
#### :eight_pointed_black_star: Microsoft RCP
#### :eight_pointed_black_star: POP3
#### :eight_pointed_black_star: IMAP
#### :eight_pointed_black_star: RADIUS
#### :eight_pointed_black_star: IRC





### :eight_spoked_asterisk: OPERATING SYSTEMS EXPLOITATION

#### :eight_pointed_black_star: WINDOWS SYSTEMS EXPLOITATION

#### :eight_pointed_black_star: LINUX SYSTEMS EXPLOITATION

### :eight_spoked_asterisk: VPN ASSESSMENT

#### :eight_pointed_black_star: SERVICE FINGERPRINTING AND SOFTWARE EVALUATION

#### :eight_pointed_black_star: IDENTIFYING CRYPTOGRAPHIC WEAKNESSES

#### :eight_pointed_black_star: EXPLOITATION OF AGGRESSIVE MODE IKE

#### :eight_pointed_black_star: BRUTE-FORCE PASSWORD GRINDING

### :eight_spoked_asterisk: IPS/IDS ASSESSMENT

#### :eight_pointed_black_star: INSERTING DATA

#### :eight_pointed_black_star: FRAGMENTING PACKETS

#### :eight_pointed_black_star: MODIFYING PACKET DATA

#### :eight_pointed_black_star: DENIAL OF SERVICE

#### :eight_pointed_black_star: OBFUSCATING

#### :eight_pointed_black_star: UNICODE EVASION TECHNIQUE

#### :eight_pointed_black_star: FALSE POSITIVE ALERT GENERATION

#### :eight_pointed_black_star: SESSION SPLICING

### :eight_spoked_asterisk: FIREWALL ASSESSMENT

#### :eight_pointed_black_star: FIREWALL IDENTIFICATION

#### :eight_pointed_black_star: IP ADDRESS SPOOFING

#### :eight_pointed_black_star: SOURCE ROOTING

#### :eight_pointed_black_star: SSH TUNNEL

### :eight_spoked_asterisk: PASSWORD CRACKING

#### :eight_pointed_black_star: ACTIVE ONLINE ATTACKS
#### :eight_pointed_black_star: PASSIVE ONLINE ATTACKS
#### :eight_pointed_black_star: OFFLINE ATTACKS



### :eight_spoked_asterisk: REMOTE NETWORK TRAFFIC ANALYSIS

## :ballot_box_with_check: FASE 4 | INTERNAL PENETRATION TESTING

### :eight_spoked_asterisk: LOCAL NETWORKS ATTACKS

#### :eight_pointed_black_star: MAC SPOOFING

#### :eight_pointed_black_star: ARP CACHE POISONING

#### :eight_pointed_black_star: CAM TABLE OVERFLOW

#### :eight_pointed_black_star: VLAN HOPPING

#### :eight_pointed_black_star: MODIFYING 802.1D STP TRAFFIC FLOW

#### :eight_pointed_black_star: ACCESSING PRIVILEGED VLANS 

#### :eight_pointed_black_star: CRACKING 802.1X CREDENTIALS

#### :eight_pointed_black_star: CDP FLOODING/SPOOFING

#### :eight_pointed_black_star: USE OF ROGUE DHCP AND WPAD

#### :eight_pointed_black_star: LLMNR, NBT-NS, AND MDNS SPOOFING

#### :eight_pointed_black_star: ROUTER IMPERSONATION VIA HSRP, EIGRP, OSPF

#### :eight_pointed_black_star: IPV6 DISCOVERY PROTOCOL SPOOFING

### :eight_spoked_asterisk: LOCAL NETWORK TRAFFIC ANALYSIS

## :ballot_box_with_check: FASE 5 | FINAL REPORT

## :ballot_box_with_check: {OPTIONAL}FASE 6 | REMEDIATION

# :boom:WEB PENETRATION TESTING (WORK IN PROGRESS...)


# :boom:WIFI PENETRATION TESTING (WORK IN PROGRESS...)


# :boom:CLOUD | DEVSECOPS PENETRATION TESTING (WORK IN PROGRESS...)


# :boom:MOBILE PENETRATION TESTING (WORK IN PROGRESS...)


# :boom:SCADA | INDUSTRIAL DEVICES PENETRATION TESTING (WORK IN PROGRESS...)

# :boom:IoT PENETRATION TESTING (WORK IN PROGRESS...)





