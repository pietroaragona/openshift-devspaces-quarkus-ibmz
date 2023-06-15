# openshift-devspaces-quarkus-ibmz
Devfile to work on quarkus projects on IBM Z architecture

Per creare il workspace seguire i seguenti step:

1. creare il workspace usando come repository https://github.com/pietroaragona/openshift-devspaces-quarkus-ibmz
2. dal menu in alto a sinistra selezionare: Terminal -> Run Task... ed esuire il task "0.1 - Initial Environment Setup" (si trova nella folder devfile) per scaricare il settings.xml ed applicare alcune configurazioni per git ed npm
3. clonare i repository su cui bissogna lavorare da terminale nella cartella /projects (cd /projects && git clone <repo url>)
4. aggiungere i repository clonati come progetti di vscode. Dal menu in alto a sinistra selezionare File -> Add folder to Workspace... ed aggiungere le cartelle dei repository clonati. 
5.salvare la configurazione come file. Dal menu in alto a sinistra selezionare File -> Save Workspace as...

Per gli accessi successivi, dopo aver startato il workspace è possibile riaprir la configurazione salvata; Dal menu in alto a sinistra selezionare File -> Open Workspace from file...
  
  
