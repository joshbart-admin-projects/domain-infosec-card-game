# Shai

Ideas for a Cyber Security tabletop exercise based on deck builder games like Dominion.

## Card types

Protection Points: Similar to victory points in Catan or Provinces (etc.) in Dominion.  These are earned with excess defensive points at the end of each round.  They can be reduced by the attacker at the end of each round by not having enough defensive points.  The game ends when the defensive team has the number of points equal to 10x the number of team members.  The score cannot go negative.
Experience: Used as currency.  A player can buy Techincal or Administrative Defenses for experience.  A player starts with their total years of experience in points and can draw additional experience equal to their tenure in their current position in place of a buy.
Technical Defenses: Defenses like firewalls and antivirus.
Administrative Defenses: Management players may implement policies or procedures that decrease the cost of technical defenses or grant minidecks.
Optional: You may start with actual assets already in your deck.  (If you have a firewall set up for your office, you start with one firewall in your deck.)

## Game play

Three decks: Technical, Management, and Attack.  

"Facilitator" plays Attack deck. This is a prebuild deck that would contain what amounts to injects (compromised workstations, DDoS attacks, stolen CCNs).  Game play is similar to MTG, with cards remaining on play field until sent to graveyard by a defensive measure.

Participants play either technical or management based on their role.  These decks are not built, but instead, all possible options for implementation are laid out on the table.  Any implementations not actually used by the company would require an additional x5 EXP to implement.

Attacker plays first.  Attacks are played face down.  On the back, they have how many detect points are needed to reveal them.  Once detected, they are turned face up to reveal their type and their defense countermeasure cost.  They remain on the play field until they are disabled with defense points.

Each player draws a full hand of 10 cards at the start of each turn, and gets a default of one buy and one implement.  They use EXP to buy Defenses, or take additional EXP.  Defenses can be implemented from their hand.  Additional buys and implements can be gained by playing cards that increase this number.  Management players play their hands before technical players.

Once all players have played, detect points are calculated and attacks are chosen to be revealed.  Once all detect points have been used, defense points are added up to disable revealed attacks.  Any left over defense points add to the total of the defense team.  Unrevealed attacks reduce the number of points.  For this reason, the attacker should keep score.

Once a round has been played, all defense players discard their hands and played cards.  If needed, they reshuffle their decks.  Play continues until the defense team earns enough points.

## Specific Cards

### Technical

Firewall (3 EXP): +5 defense. +1 draw. +1 implement.
Firewall logs (1 EXP): +1 detect; requires firewall.
Endpoint Antivirus (2 EXP): +1 defense.
Sysmon: +5 detect.
SIEM: +10 detect. +1 implement.
Vulnerability Scan: +1 defense. +1 implement.
System Patch: +5 defense.
User report (7 EXP): +20 detect. +2 draw. +1 implement. Disables phishing regardless of defense cost.

### Administrative

Policy: -1 experience cost to related Technical cards.
Procedure: -3 experience cost to related Technical cards. provides access to minideck. Requires policy.
Phishing Training: -1 experience cost to related Technical cards; cost: 15 EXP
Monthly Security Awareness Training: -1 experience to related Technical cards; cost: 1 EXP
