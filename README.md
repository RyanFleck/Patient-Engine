# Patient-Engine
Dungeon management system with web-based local web GUI for phones &amp; computers. Enables local party with remote members.

**Planned Features**

1. Intended for use in three ways:
    1. Friends gathered at table, utilizing system to manage inventory and stats of characters.
    1. Friends online, utilizing system to play:
      1. In real-time, together.
      1. Turn by turn over a working day.
1. API for adding/manipulating entries in the item, spell, monster manuals.
1. Utilize [Web Speech API](https://developers.google.com/web/updates/2013/01/Voice-Driven-Web-Apps-Introduction-to-the-Web-Speech-API) to transcribe player/dm chatter to a log that can be read when idle players need to catch up.
    1. Alternatively, chatter could be routed directly through the web application and processed server side.
1. Character management system including statistics, items, spells.
1. Call Marvel API to populate *Monster Manual* with villains and dark heroes.

**Development Commands**
1. Build: `gradle build -i`
1. Test: `gradle integrationTest -i`
1. Run Instance:
    - Start `gradle libertyStart`
    - Stop `gradle libertyStop`
    - Run `gradle libertyRun`
    
See <http://localhost:9080/PatientEngine/>

**Resources**
1. [Getting started with Open Liberty](https://openliberty.io/guides/getting-started.html)
2. [JDBC and PostgreSQL](http://www.postgresqltutorial.com/postgresql-jdbc/connecting-to-postgresql-database/)
