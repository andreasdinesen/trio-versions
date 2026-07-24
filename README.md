# trio-versions

Nyeste versionsnumre for Trio-værktøjerne. Bruges af
[TrioHelper](https://github.com/andreasdinesen/TrioHelper)s opdateringstjek
som fallback, når git-tjekket ikke er muligt (fx ZIP-download uden `.git`
eller manglende GitHub-adgang) — filen kan hentes anonymt, da dette repo er
offentligt.

Filen `versions.json` opdateres med `publish_versions.py` fra
TrioHelper-repoet, hver gang et af værktøjerne får ny version.

Indeholder kun versionsnumre — ingen kode eller data fra værktøjerne.
