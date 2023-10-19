# TeamDev Hack2023


## 4 Path possibili: 

### 1) Implementare un provider per Arbitrer
  
Implementare un provider, seguendo la falsa riga dei due provider gia implementati (RabbitMQ e Kafka) che permetta ad Arbitrer di comunicare attraverso Redis. 

*Pattern di riferimento:*

* CQRS : https://learn.microsoft.com/it-it/azure/architecture/patterns/cqrs

* Mediator: https://www.dotnettricks.com/learn/designpatterns/mediator-design-pattern-c-sharp


*Strumenti richiesti:*

* dotnet 7.x: https://learn.microsoft.com/it-it/dotnet/core/whats-new/dotnet-7

* MediatR 12.x  : https://github.com/jbogard/MediatR

* Arbitrer 12.x : https://github.com/TeamDev-it/arbitrer

* Redis: https://redis.io/


Codice a cui fare riferimento per l'implementazione: 

https://github.com/TeamDev-it/arbitrer/tree/master


### 2) Implementare Arbitrer in Phyton

Fare porting del progetto Arbitrer (anche senza i provider) in Phython, 


* python: https://www.python.org/

* Arbitrer: https://github.com/jbogard/MediatR

* Mediator Py : https://github.com/dlski/python-mediator
              : https://github.com/megafetis/mediatr_py


### 3) Implementazione message-bus di comunicazione con typescript o javascript per applicazioni frontend 

Va implementano un messagebus di comunicazione frontend per moduli ESM in modo tale che possa essere utilizzato in implementazioni a micro-frontend

* nodejs: https://nodejs.org/it

* typescript: https://www.typescriptlang.org/

* microfrontend: https://riccardogmoschetti.github.io/micro-frontends/

* modulo di riferimento: https://riccardogmoschetti.github.io/micro-frontends/



### 4) Implementare un progetto a microservizi

Implementare un progetto a microservizi utilizzando una architettura CQRS con .net ed EntityFramework


* CQRS : https://learn.microsoft.com/it-it/azure/architecture/patterns/cqrs

* Mediator: https://www.dotnettricks.com/learn/designpatterns/mediator-design-pattern-c-sharp

* Esempio di progetto, ma non vincolante: https://www.diag.uniroma1.it/~lenzerin/index.html/files/2023-02-15.pdf


### Quando finisce ? 

La partecipazione termina il 31/10 alle 24. 

### Come fare commit. 

Va fatta una pullrequest su questo repo entro il termine del'hackaton. 

