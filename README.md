# KYPO Cyber Range Platform Demo Training

Linear game for [KYPO CRP](https://docs.crp.kypo.muni.cz/).

Follow [general instructions](https://docs.crp.kypo.muni.cz/basic-concepts/typical-training-workflow/training-workflow-cloud/) to set up the game.

## Game Levels Summary
- `nmap` port scanning
- `hydra` password guessing at `telnet` 
- privilege escalation using misconfigured `sudo`

## Topology summary
|Host|Image|Flavor|
|-|-|-|
|server|ubuntu-focal-x86_64|standard.small|
|client|ubuntu-focal-x86_64|standard.small|
|router|debian-9-x86_64|standard.small|

## License and Credits
[MIT License](./LICENSE)

**Leading author:** Zdeněk Vydra

**Contributors:** Jakub Čegan, Tomáš Sapák, Kamil Andoniadis, Igor Ignác, Juraj Paluba, Dominik Pilár, Michal Urban, Tomáš Kacvinský
