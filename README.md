# Finventure: preview pentru testare

Versiunea în lucru a jocului (ramura `extindere` din [thinkINGbig-ro/finventure](https://github.com/thinkINGbig-ro/finventure)), pentru testarea echipei pe telefon:

**https://mihaimpmo.github.io/finventure-preview/**

- Se actualizează singură: workflow-ul din `.github/workflows/preview.yml` verifică la câteva minute dacă ramura `extindere` s-a schimbat și o publică. Commit-ul publicat e în [`versiune.txt`](https://mihaimpmo.github.io/finventure-preview/versiune.txt). Publicare imediată: tab-ul Actions → „Preview extindere” → Run workflow.
- Salvările de aici folosesc cheile `finventure-preview.*` și sunt separate de jocul publicat.
- Repo-ul nu conține codul jocului; îl preia la fiecare publicare.
- GitHub oprește programările unui repo fără activitate de 60 de zile; atunci reactivează workflow-ul din tab-ul Actions.
