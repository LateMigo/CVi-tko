# Projekt zakładający założenie strony do zamieszczania mojego CV na hostingu firebase do podglądu dla mnie oraz dla firm rekrutujących
 
## Deployment

Strona jest wdrażana automatycznie na Firebase Hosting przez GitHub Actions:

- push do `main` → deploy na produkcję (`firebase-hosting-merge.yml`)
- pull request → podgląd na osobnym preview channel (`firebase-hosting-pull-request.yml`)
- autoryzacja przez service account zapisany w GitHub Secrets

Ten sam schemat CI/CD skonfigurowałem wcześniej dla strony firmowej podczas stażu DevOps.
