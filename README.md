# NBATools: NBA Weekly Stat Projector

NBA Weekly Stat Projector is an online tool that projects every NBA player's stats for the upcoming week by factoring in their:
  1. Average of the last 8 games (with the last 3 games weighed more heavily)
  2. Number of games in the week
  3. Average of each team playing against for the week
  4. Missed games in the past 8 games

To try this tool in live action, visit [http://nbatools.bitballoon.com][firstlink]

### Utilized Services

This NBA tool is currently implementing the following services: 
* [Google Spreadsheets][Spreadsheet] - Database to store the calculated statistics
* [Google Spreadsheets App Scripts][AppScript] - Perform automatic calculations weekly
* [NBA API][NBAPI] - Retreive data through NBA's API
* [ImportJSON][ImportJSON] - Import data retreived from NBA's API into a Google Spreadsheet
* [BootStrap][BootStrap] - Web design
* [DataTables][Datatables] - Table design
* [Select2][Select2] - Select box dropdown design

### Preview
<img src="http://i.imgur.com/wdDVuC4.png?1">

##
[firstlink]: <http://nbatools.bitballoon.com/>
[Spreadsheet]: <https://docs.google.com/spreadsheets/d/1m7Ir_YuS21g-gAEn3D6cwjW8Sdp7f8XOUeZxYiJEOgk/edit#gid=2075237903>
[AppScript]: <https://github.com/HenleyKuang/NBA-Weekly-Stats-Analysis/blob/master/Google%20Spreadsheet%20AppScript.js>
[NBAPI]: <http://www.rubydoc.info/gems/nba_stats/>
[ImportJSON]: <http://blog.fastfedora.com/projects/import-json>
[BootStrap]: <http://getbootstrap.com/>
[Datatables]: <http://datatables.net/>
[Select2]: <https://select2.github.io/>
