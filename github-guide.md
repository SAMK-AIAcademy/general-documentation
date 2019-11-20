# GitHub guidelines

Pohjana: [Github Flow - Guide](https://guides.github.com/introduction/flow/)

## Repon luonti

Projektia varten organisaatioon (SAMK-AIAcademy) luodaan projektille tiimi, johon kaikki projektin jäsenet kuuluvat.

Projektipäällikkö luo projektille repon organisaation alle ja liittää tiimin repoon. Tiimille annetaan repoon Triage oikeudet, tällöin tiimi pystyy kloonaaman ja käsittelemään pull requesteja, mutta ei työntämään muutoksia suoraan repoon. Devaus tapahtuu forkkausta ja pull requesteja käyttäen.


## Devaus

Forkkaa organisaation repo itsellesi ja käytä sitä kehittämiseen.

Master branchissa pidetään toimiva (deployable) versio ja kehitys tapahtuu feature-brancheissa. Näistä brancheista luodaan pull requestit alkuperäiseen (organisaation) repoon.


## PR:t

Pull requestia ei saa hyväksyä sen author. Joku muu tiimin jäsen käy lukemassa ja (mahdollisesti) hyväksymässä ehdotuksen.

Tällä code review toiminnalla pyritään välttämään selvien virheiden läpimenoa (esim turhat logitukset).

## Kanban-board ja issuet

Käytetään Project-boardia projektin hallintaan sekä GitHubin issueita tikettien hallintaan.

Tällä mahdollistetaan eri työvaiheiden etenemisen hallittu seuranta.

Nämä työkalut helpottavat myös dokumentaation ylläpitoa.