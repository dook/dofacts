![logo](https://raw.githubusercontent.com/dook/dofacts/db74541b6a7e2274f9f521772ecc4985feac82bb/assets/logo.svg)

# DoFacts!

DoFacts is an open-source project created due to pandemic. It faces up to too much information about COVID-19 where true and fake news intertwine.

Project is split into a few parts:

- extension - allows on reporting COVID-19 news
- collector - collects reports from extension and distribute them between fact-checkers
- panel - frontend app for verifying news
- panel-api - api for panel
- panel - website for displaying verified information
- panel-api - api for portal

Thanks to division to multiple services DoFacts is able to handle huge traffic without problems. Even if any service will fail the rest of them will be still available for users.

This project is licensed under the MIT License - see the LICENSE file in each service
