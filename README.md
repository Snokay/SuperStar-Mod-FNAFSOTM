# SuperStar Mod – Five Nights at Freddy's: Secret of the Mimic

![SuperStar Mod](visuel/Logo%20MIMIC%20%E2%80%93%20Secret%20of%20the%20Superstar%20Mod.png)

**[English](#english)** · **[Français](#français)**

---

## English

An ultra-hardcore mode for **FNaF: Secret of the Mimic** (Steam, PC). Faster and sharper animatronics, fewer
hiding spots, hidden gifts and upgrade stations, and a gold star on the title screen once you beat the game with
the mod on.

### What it changes

- **Animatronics**: faster patrols and chases, longer sight range, faster reactions, sharper hearing, and they
  keep chasing you for 2 minutes after losing sight of you. Dolly, Chica, the cupcakes and the chases on rails
  have their own tuning.
- **Levels**: most lockers and hiding spots removed, mouse traps and gifts moved to risky spots (some in other
  areas), Data Diver upgrade stations hidden behind security doors, harder vent puzzle, a harder White Tiger.
- **Doubles**: the Inventor's House has two Mimics instead of one.
- **Custom voices and posters** here and there (keep your eyes open).
- **Keyboard layout**: a "Keyboard layout" line in Options > Controls (QWERTY / AZERTY / QWERTZ).
- **The star**: the logo on the title screen shows an empty star. Finish the game with SuperStar on and it
  becomes a gold star (saved next to your game saves, so it survives a reinstall).

### Installation

**Option A – Launcher (easiest)**

1. Download `SuperStar-Mod-SotM-<version>_launcher.zip` from the
   [Releases](https://github.com/Snokay/SuperStar-Mod-FNAFSOTM/releases) page and extract it anywhere.
2. Run `SuperStar_Mod_Launcher.exe` (Windows may warn about an unknown app: *More info* > *Run anyway*).
3. It finds the game by itself (or click *Game folder*), then click **Install** and **PLAY**.

The launcher also updates the mod, switches between **SuperStar** and the **vanilla** game in one click, and
uninstalls everything.

**Option B – Manual**

1. Download `SuperStar-Mod-SotM-<version>_manuel.zip` from the
   [Releases](https://github.com/Snokay/SuperStar-Mod-FNAFSOTM/releases) page.
2. Open the game folder: in Steam, right-click **Five Nights at Freddy's: Secret of the Mimic** >
   **Manage** > **Browse local files**.
3. Extract the zip **into that folder** and accept merging the folders. You should end up with
   `FNAF_SOTM\Binaries\Win64\dwmapi.dll` and `FNAF_SOTM\Content\Paks\zzVoixSotM_P.pak`.
   (If you already use other UE4SS mods, keep your own `mods.txt` and add the lines `SuperstarSotM : 1`,
   `ObjetsSotM : 1` and `ClavierSotM : 1` above `Keybinds`.)
4. Start the game: the new logo with the star means the mod is running.

**Uninstall** (manual): delete `FNAF_SOTM\Binaries\Win64\dwmapi.dll`, the `FNAF_SOTM\Binaries\Win64\ue4ss` folder and
`FNAF_SOTM\Content\Paks\zzVoixSotM_P.pak`.

Start a **new game** for the full experience: some changes depend on your progress.

### Keys

| Key | Action |
|---|---|
| F8 | Turn SuperStar on / off (no star if it is off when the credits roll) |
| F7 | Enemy diagnostic (written to `ue4ss\Mods\SuperstarSotM\journal.log`) |
| F6 | Spawn a double of the nearest enemy |
| F4 / F3 | Modding tools: position report / reload `deplacements.txt` |

### Credits

- Mod by **Snokayy**.
- Idea from the **Superstar Mode** for FNaF: Security Breach by **blanana** (blanana_m).
- Built on [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (MIT license, included).

---

## Français

Un mode ultra hardcore pour **FNaF : Secret of the Mimic** (Steam, PC). Des animatroniques plus rapides et plus
attentifs, moins de cachettes, des cadeaux et des stations d'amélioration cachés, et une étoile dorée sur
l'écran titre quand tu finis le jeu avec le mod.

### Ce qui change

- **Animatroniques** : patrouilles et poursuites plus rapides, vue plus longue, réactions plus vives, ouïe plus
  fine, et ils te poursuivent encore 2 minutes après t'avoir perdu de vue. Dolly, Chica, les cupcakes et les
  poursuites sur rail ont leurs propres réglages.
- **Niveaux** : la plupart des casiers et cachettes retirés, bacs de souris et cadeaux déplacés à des endroits
  risqués (parfois dans une autre zone), stations d'amélioration du Data Diver cachées derrière des portes de
  sécurité, puzzle des conduits plus dur, Tigre Blanc plus dur.
- **Doubles** : la maison de l'inventeur a deux Mimics au lieu d'un.
- **Voix et affiches personnalisées** un peu partout (ouvre l'œil).
- **Disposition du clavier** : une ligne « Disposition du clavier » dans Options > Contrôles (QWERTY / AZERTY /
  QWERTZ).
- **L'étoile** : le logo de l'écran titre affiche une étoile vide. Finis le jeu avec SuperStar actif et elle
  devient dorée (enregistré à côté de tes sauvegardes, donc gardé même après une réinstallation).

### Installation

**Option A – Launcher (le plus simple)**

1. Télécharge `SuperStar-Mod-SotM-<version>_launcher.zip` sur la page
   [Releases](https://github.com/Snokay/SuperStar-Mod-FNAFSOTM/releases) et extrais-le où tu veux.
2. Lance `SuperStar_Mod_Launcher.exe` (Windows peut prévenir d'une application inconnue : *Informations
   complémentaires* > *Exécuter quand même*).
3. Il trouve le jeu tout seul (sinon *Dossier du jeu*), puis clique sur **Installer** et **JOUER**.

Le launcher met aussi le mod à jour, passe de **SuperStar** au **jeu normal** en un clic et désinstalle tout.

**Option B – Manuelle**

1. Télécharge `SuperStar-Mod-SotM-<version>_manuel.zip` sur la page
   [Releases](https://github.com/Snokay/SuperStar-Mod-FNAFSOTM/releases).
2. Ouvre le dossier du jeu : dans Steam, clic droit sur **Five Nights at Freddy's: Secret of the Mimic** >
   **Gérer** > **Parcourir les fichiers locaux**.
3. Extrais le zip **dans ce dossier** et accepte de fusionner les dossiers. Tu dois obtenir
   `FNAF_SOTM\Binaries\Win64\dwmapi.dll` et `FNAF_SOTM\Content\Paks\zzVoixSotM_P.pak`.
   (Si tu utilises déjà d'autres mods UE4SS, garde ton `mods.txt` et ajoute les lignes `SuperstarSotM : 1`,
   `ObjetsSotM : 1` et `ClavierSotM : 1` au-dessus de `Keybinds`.)
4. Lance le jeu : le nouveau logo avec l'étoile indique que le mod fonctionne.

**Désinstaller** (manuel) : supprime `FNAF_SOTM\Binaries\Win64\dwmapi.dll`, le dossier `FNAF_SOTM\Binaries\Win64\ue4ss`
et `FNAF_SOTM\Content\Paks\zzVoixSotM_P.pak`.

Commence une **nouvelle partie** pour profiter de tout : certains changements dépendent de ta progression.

### Touches

| Touche | Action |
|---|---|
| F8 | Active / désactive SuperStar (pas d'étoile s'il est coupé au générique) |
| F7 | Diagnostic des ennemis (dans `ue4ss\Mods\SuperstarSotM\journal.log`) |
| F6 | Fait apparaître un double de l'ennemi le plus proche |
| F4 / F3 | Outils de modding : relevé de position / relecture de `deplacements.txt` |

### Crédits

- Mod de **Snokayy**.
- Idée tirée du **Superstar Mode** de FNaF : Security Breach, par **blanana** (blanana_m).
- Construit avec [UE4SS](https://github.com/UE4SS-RE/RE-UE4SS) (licence MIT, inclus).
