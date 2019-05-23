# Shai

Ideas for a Cyber Security tabletop exercise based on deck builder games like Dominion.

## Card types

Protection Points: similar to victory points in Catan or Provinces (etc.) in Dominion.  These would be purchased through use of Technical or Administrative Defenses cards.
Technical Defenses: Defenses like firewalls and antivirus.
Experience: Used as currency.  A player can buy protective measures for experience.  A player may take, on each turn, the number of experience points equivalent to the number of years in his current position.
Administrative Defenses: Management players may implement policies or procedures that decrease the cost of technical measures.

## Game play

Three decks: Technical, Management, and Attack.  

"Facilitator" plays Attack deck. This is a prebuild deck that would contain what amounts to injects (compromised workstations, DDoS attacks, stolen CCNs).  Game play is similar to MTG, with cards remaining on play field until sent to graveyard by a defensive measure.

Participants play either technical or management based on their role.  These decks are not built, but instead, all possible options for implementation are laid out on the table.  Any implementations not actually used by the company would require an additional x5 EXP to implement.  Participants play in three phrases: Buy, implement, and spar.  Options used in these phases 

Attacker plays first.  Attacks are played face down.  On the back, they have how many detection points are needed to reveal them.  Recon attacks have the least amount of detection.  Intrusion attacks require the most amount of detection.

## Specific Cards

### Technical

Firewall: +5 to defense.
Firewall logs: +1 to detection; requires firewall
Endpoint Antivirus: +1 to defense; cost: 2 EXP
Sysmon: +5 to detection.
SIEM: +10 to detection.
Vulnerability Scan: +1 to defense.
User report: +20 to detection; 7 EXP

### Administrative

Policy: -1 experience cost to related Technical cards
Procedure: -3 experience cost to related Technical cards
Phishing Training: -1 experience cost to related Technical cards; cost: 15 EXP
Monthly Security Awareness Training: -1 experience to related Technical cards; cost: 1 EXP
