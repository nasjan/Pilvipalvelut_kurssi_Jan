---
layout: default
title: Viikko 2
---

2.3 __Jekyll-sivuston julkaisu voidaan automatisoida GitHub Actionsilla.__ Kun uusi commit tehdään main-haaraan, GitHubin pilvipalvelu käynnistää työnkulun (workflown), joka rakentaa sivuston Jekyllillä ja julkaisee sen automaattisesti GitHub Pagesiin. Tämä vähentää manuaalista työtä ja varmistaa, että sivu pysyy aina ajan tasalla.

__Web-sovellukselle CI/CD-putkisto voidaan rakentaa työkaluilla esim. GitHub Actions, GitLab CI tai Jenkins.__ CI-vaiheessa koodi testataan ja rakennetaan automaattisesti jokaisen muutoksen yhteydessä. CD-vaiheessa hyväksytty versio julkaistaan automaattisesti palvelimelle tai pilviympäristöön (esim. AWS, Azure, Vercel). Tämän putkiston avulla tiimi voi kehittää ohjelmaa jatkuvasti pienissä osissa ilman manuaalisia asennuksia. Näin virheet löytyvät nopeammin ja julkaisut pysyy yhtenäisinä.