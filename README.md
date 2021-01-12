# CodeployAcademyWso2
Esercizi wso2esb

Questo progetto contiene esempi relativi all'utilizzo di WSO2 ESB.

- example
Contiene esempi semplici per prendere familiarità con l'ambiente di sviluppo.
- workshop1
Sono qui presenti gli esempi utilizzati durante il primo workshop.
- workshop2
Sono qui presenti gli esempi utilizzati durante il secondo workshop.

Gli esercizi saranno svolti con la versione WSO2 ESB 5.0.0
Verrà approfondito durante il corso la nuova versione di WSO2 Enterprise Integrator con un focus su ESB
e sulle differenze con la versione 5.0.0 

## setup ambiente
- è necessario avere configurato JAVA sul proprio ambiente
- scaricare la versione server wso2 esb 5.0.0 al link seguente https://wso2.com/integration/previous-releases/
- sempre dallo stesso link scaricare la versione di Tooling full distribution

N.B. Il developer studio (tooling) sono un ambiente Eclipse con plugin wso2 già preimpostati.
Ho individuato un errore nell'avvio di tale IDE su MacBookPro Catalina 10.15.7
Per risolvere tale anomalia:
In the Eclipse.app folder:

xattr -d com.apple.quarantine Eclipse.app/