# Mail Classifier

Le e-mail sono punti cardine della comunicazione nel mondo moderno. Di conseguenza, la capacità di classificarle accuratamente e, nello specifico, di filtrare lo spam per evitare la congestione della posta in arrivo, è di grande importanza.

Questo progetto valuta e confronta quattro modelli distinti:

- SVC (Support Vector Classification)
- Alberi decisionali (Decision Trees)
- Random Forest
- Reti Neurali

L'obiettivo primario è identificare il modello che offra le migliori prestazioni predittive mantenendo al contempo un basso utilizzo di memoria. L'efficienza delle risorse è un punto critico, poiché le infrastrutture che ospitano questi modelli (come i dispositivi IoT) hanno spesso risorse hardware limitate. Tali risorse devono essere condivise tra più funzioni e non possono essere interamente dedicate al filtraggio delle e-mail.

Il notebook è organizzato nelle seguenti sezioni:
1. Pre-processing e Utility
2. Definizione delle metriche di errore
3. SVM (Support Vector Machine)
4. Alberi decisionali
5. Random Forest
6. Multi Layer Perceptron
7. SVM alternativa
8. Conclusioni e note aggiuntive
