# Free Protest

![Liberty Leading the People](https://upload.wikimedia.org/wikipedia/commons/thumb/0/02/La_Libert%C3%A9_guidant_le_peuple_-_Eug%C3%A8ne_Delacroix_-_Mus%C3%A9e_du_Louvre_Peintures_RF_129_-_apr%C3%A8s_restauration_2024.jpg/960px-La_Libert%C3%A9_guidant_le_peuple_-_Eug%C3%A8ne_Delacroix_-_Mus%C3%A9e_du_Louvre_Peintures_RF_129_-_apr%C3%A8s_restauration_2024.jpg)

*"Liberty Leading the People" (1830) by Eugène Delacroix — [Wikipedia](https://en.wikipedia.org/wiki/Liberty_Leading_the_People)*

**A Facebook app that automatically generated preventive Habeas Corpus documents to protect protesters during Brazil's 2013 demonstrations.**

---

## About

In June 2013, a wave of massive protests swept across Brazil -- events known as the *Jornadas de Junho* (June Journeys), the *Brazilian Spring*, or the *2013 Confederations Cup protests*.

![Protests at Brazil's National Congress, June 17, 2013](https://upload.wikimedia.org/wikipedia/commons/4/4b/Protesto_no_Congresso_Nacional_do_Brasil%2C_17_de_junho_de_2013.jpg)

During this period, many protesters were being illegally arrested. Volunteer lawyers were manually filling out preventive *Habeas Corpus* forms with pen and paper on the streets. This project was born from a simple insight: **what if people could automatically generate a legally valid preventive Habeas Corpus through a Facebook app?**

That is exactly what this team built. The app pulled user data from Facebook (with permission) and generated a proper legal document that could help protect people from unlawful detention.

## How It Worked

1. User accessed the app through Facebook
2. The app collected basic personal information (name, ID) with the user's consent
3. A preventive *Habeas Corpus* PDF was automatically generated and ready for use

## Tech Stack

- **Java** -- Android application
- **Facebook API** -- User authentication and data collection
- **Android 2.2+** -- Minimum supported version
- Deployed on Heroku as a Facebook-integrated web app

## Outcome

The project was built in 2014 in anticipation of renewed protests during the World Cup. Unfortunately, the large-scale demonstrations of 2013 did not recur. The Facebook page received around 300 likes and the app was used approximately 30 times. A good idea that missed its window of timing.

## Demo (Historical)

- [Facebook page](https://www.facebook.com/protestolivrehc/) (may no longer be active)
- [Facebook app](https://apps.facebook.com/protestolivre/) (may no longer be active)

## Team

This was a multidisciplinary team effort, built for the *Vai Mudar na Copa* contest:

- **Pedro Delfino** -- Project lead / Product Owner (conceived the idea and managed the team)
- **Thiago Cavalcante** -- Lead developer and main author of the code
- **Italo Ferreira dos Santos** -- Design
- **Fernanda Almeida Fernandes de Oliveira** -- Legal
- **Ricardo Carrion** -- Legal
- **Luan Camargo** -- Legal

## Language Note

The application interface and generated legal documents are in Portuguese, as this was built specifically for the Brazilian legal context.
