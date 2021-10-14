# Project Title
Analisi chimica di campioni biologici

# Project Description
Il sistema gestisce le richieste di analisi chimiche presentate dal cittadino o da un tecnico delegato ai laboratori regionali di analisi, consentendo a questi ultimi la registrazione dei risultati delle analisi. Il sistema è predisposto per il pagamento delle richieste presentate con il sistema di pagamento della pubblica amministrazione PagoPA tramite un altro progetto del CSI Piemonte, che potrà essere fornito su richiesta.

# Getting Started
Il prodotto AGRICHIM è composto dalle seguenti componenti:
- [AGRCFO](https://github.com/regione-piemonte/agrichim-agrcfo) (web application di front office che consente il caricamento e la presentazione delle richieste di analisi)
- [AGRCBO](https://github.com/regione-piemonte/agrichim-agrcbo) (web application di back office che consente ai laboratori regionali di registrare i risultati delle analisi)
- [AGRICHIMDB](https://github.com/regione-piemonte/agrichim-agrichimdb) (script per la creazione ed il mantenimento del DB proprietario)
- [AGRICHIMDB](https://github.com/regione-piemonte/agrichim-agrichimpl) (script per la definizione di stored procedure e function)

# Prerequisites
I prerequisiti per l'installazione delle componenti sono i seguenti:
## Software
- [JDK 8](https://www.apache.org)
- [Apache 2.4](https://www.apache.org)
- [RedHat JBoss 6.4 GA](https://developers.redhat.com)  
- [PostgreSQL 9.2](https://www.oracle.com)  

- Tutte le librerie elencate nel file BOM.csv devono essere accessibili per compilare il progetto. Le librerie sono pubblicate su http://repart.csi.it, ma per semplicità sono state incluse nella cartella lib/ di ogni singola componente, ad esclusione della libreria weblogic-client-3.1.0.jar, che è utilizzata dalle componenti AGRCFO e AGRCBO per invocare servizi esterni con protocollo t3 e che deve essere scaricata autonomamente dal sito di Oracle.

# Versioning
Per la gestione del codice sorgente viene utilizzato Git. Per la gestione del versioning si fa riferimento alla metodologia [Semantic Versioning](https://semver.org) 

# Copyrights
(C) Copyright 2020 Regione Piemonte

# License
Questo software è distribuito con licenza EUPL-1.2.
Consultare i file EUPL v1_2 IT-LICENSE.txt e EUPL v1_2 EN-LICENSE.txt per maggiori dettagli.
