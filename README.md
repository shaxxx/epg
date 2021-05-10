# Using generated XMLTV sources with EPGImport enigma2 plugin
- install latest EPGImport plugin that supports https protocol
- download [krkadoni.channels.xml](https://raw.githubusercontent.com/shaxxx/epg/main/output/krkadoni.channels.xml) file
- download [krkadoni.sources.xml](https://raw.githubusercontent.com/shaxxx/epg/main/output/krkadoni.sources.xml) file
- edit krkadoni.channels.xml file with channel references from your enigma2 settings
- upload edited file krkadoni.channels.xml and krkadoni.sources.xml to /etc/epgimport folder on your enigma2 receiver
- run EPGImport plugin, go to sources, select everything under Krkadoni XMLTV
- import EPG data

