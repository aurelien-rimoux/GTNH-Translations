# Glossaire de traduction fr_FR – GTNH

Référence commune pour traduire le livre de quêtes (BetterQuesting) et les autres fichiers
de GTNH en français. **Avant de traduire un terme, vérifiez ici. Si un terme manque, ajoutez-le.**

Le but : qu'un même mot anglais soit toujours rendu par le même mot français, d'une quête à l'autre.

---

## 0. Règle d'or : les noms tels que NEI les affiche

**Un nom d'objet, de machine, de bloc ou de matériau s'écrit exactement comme NEI l'affiche avec le jeu en français.**
Le joueur doit pouvoir copier le nom de la quête dans la recherche NEI et trouver l'objet.

Dans la pratique (vérifié dans `fr_FR/GregTech_fr_FR.lang` et `Ender IO[enderio]`) :

| Catégorie | Langue | Exemples |
|---|---|---|
| Machines (GregTech, EnderIO, GT++…) | **anglais** | Fluid Heater, Mixer, Chemical Reactor, Electric Blast Furnace (EBF), Vacuum Freezer, Cutting Machine, Capacitor Bank, Farming Station, Super Tank |
| Objets / composants | **anglais** | Machine Hull, Small Coil, SMD Inductor, Data Stick, Petri Dish, Field Generator, Energy Hatch, World Anchor |
| Circuits | **anglais** | Integrated Processor, Processor Assembly, Workstation, Mainframe, Microprocessor, Wafer, NAND Chip, SoC |
| Sigles | **anglais** | SMD, NaK, EU, RF, NEI, AE2, PTFE, LCR, EBF, UUM, UUA, TPS, HSS-G |
| **Matériaux GregTech** | **français** (traduits en jeu) | Titane, Acier au Tungstène, Néodymium, Platine, Chlore, Ammoniac, Acide Nitrique… (voir section 4) |
| Matériaux EnderIO | **anglais** (non traduits en jeu) | Vibrant Alloy, Energetic Alloy, Vibrant Crystal, Soularium |
| Noms communs génériques | **français** | lingot, poudre, plaque, cellule, minerai, filon, feuille |

> Exemple : « Combinez du TiCl4 avec du Magnésium dans un EBF HV pour obtenir un lingot chaud de Titane. »
> Exemple : « Fabriquez un Fluid Heater MV ou HV. »

Si la traduction GregTech change un jour (machines traduites), on s'aligne sur elle.

**Titres de quête** : si le titre est un nom d'objet/machine, on le garde tel quel (« §5§lFluid Heater », « §5§lSMD Diodes ») ;
sinon on le traduit (« §5§lDimension personnelle », « §5§lFabrication automatisée »).

---

## 1. Règles générales

| Règle | Détail |
|---|---|
| Registre | **Vouvoiement** systématique (« Fabriquez-en un », « vous aurez besoin… »). |
| Ton | Garder l'humour et les clins d'œil de l'original, sans traduction mot à mot. |
| Codes de format | Ne **jamais** modifier `§5§l`, `§r`, `§2`, `%n`, `%%`, `[note]…[/note]`, `[warn]…[/warn]`, `[url]…[/url]`. |
| Titres de quête | Garder le code couleur d'origine (`§5§l` pour HV, etc.). Majuscule au premier mot uniquement pour un titre traduit. |
| Ponctuation | Espace avant `?` `!` `:` `;` (typographie française). Guillemets « … ». |
| Nombres | Garder les nombres tels quels (`60k`, `2A`, `1 000 000`). |
| Commandes | Les commandes ne se traduisent pas : `/pspace allow-worldgen-change DIMID`. |
| Noms de mods | Jamais traduits : GregTech, GT++, EnderIO (EIO), AE2, Thaumcraft, Blood Magic, Twilight Forest, CropsNH… |
| Paliers de tension | Jamais traduits : ULV, LV, MV, HV, EV, IV, LuV, ZPM, UV, UHV, UEV, UIV, UMV, UXV, MAX. |
| Unités | EU, EU/t, RF/t, A (ampère), L, t (tick), s. |
| Noms de lignes de quête | Format `Tier N - XX` conservé (ex. « Tier 3 - HV »). Les noms d'onglets cités (« Multiblock Goals », « Space Race »…) restent en anglais tant que l'onglet n'est pas traduit. |

---

## 2. Termes de jeu généraux (à traduire)

| Anglais | Français | Remarque |
|---|---|---|
| craft / to craft | fabriquer / fabrication | Éviter « crafter ». |
| crafting table | établi | |
| recipe | recette | |
| quest / questline / tab | quête / chapitre / onglet | |
| to skip a quest | passer cette quête | « tenir X en main pour passer cette quête ». |
| hold in your hand | tenir en main | |
| tier | tier | Masculin : « ce tier ». |
| voltage tier | palier de tension | |
| early / late game | début / fin de partie | |
| mob | monstre / créature | « mob » toléré en contexte technique. |
| ore / small ore / vein | minerai / petit minerai / filon | |
| dust / ingot / nugget / plate / sheet / rod | poudre / lingot / pépite / plaque / feuille / tige | |
| hot ingot | lingot chaud | |
| cell | cellule | |
| fluid / liquid / gas / molten | fluide / liquide / gaz / en fusion | |
| byproduct | sous-produit | |
| slurry | boue | |
| to centrifuge / to macerate | centrifuger / broyer | |
| to cut / wafer cutting | découper | |
| setup | installation / montage | |
| stockpile | faire des réserves | |
| shift-right-click | Maj + clic droit | |
| server admin / operator | administrateur / opérateur du serveur | |
| lag | lag | |
| loot bag | sac de butin | |
| shanks (hunger) | barre de faim | |
| Moon | Lune | Majuscule. Idem Mars… |
| the End / the Nether | l'End / le Nether | |
| cleanroom | salle blanche | Le bloc reste « Cleanroom ». |
| overclock (OC) | overclock (OC) | Terme consacré. |
| circuit (générique) | circuit | « circuits EV », « circuits IV ». |
| circuit line | gamme de circuits | |

---

## 3. Machines et objets GregTech (restent en anglais)

Rappel : la machine garde son nom anglais, mais la phrase autour est en français.
« un Chemical Reactor HV », « votre Distillation Tower », « dans un Vacuum Freezer ».

| Anglais (à garder) | Abréviation courante |
|---|---|
| Electric Blast Furnace | EBF |
| Large Chemical Reactor | LCR |
| Precision Laser Engraver | PLE |
| Circuit Assembler | CA |
| Machine Hull | — |
| Energy Hatch | — |

---

## 4. Matériaux (noms français tels qu'en jeu)

| Anglais | Français (NEI) |
|---|---|
| Neodymium | Néodymium |
| Titanium | Titane |
| Tungstensteel | Acier au Tungstène |
| Steel / Stainless Steel | Acier / Acier inoxydable |
| Aluminium | Aluminium |
| Bauxite / Ilmenite / Rutile / Chromite | Bauxite / Ilménite / Rutile / Chromite |
| Bauxite Slurry / Bauxite Slag | Boues de Bauxite / Scories de Bauxite |
| Alumina / Aluminium Hydroxide / Sodium Aluminate | Alumine / Hydroxyde d'aluminium / Aluminate de Sodium |
| Platinum / Palladium / Iridium / Osmium | Platine / Palladium / Iridium / Osmium |
| Gallium / Zinc / Sphalerite | Gallium / Zinc / Sphalérite |
| Chalcopyrite / Pentlandite / Nickel | Chalcopyrite / Pentlandite / Nickel |
| Bastnasite / Monazite / Rare Earth | Bastnasite / Monazite / Terres Rares |
| Meteoric Iron | Fer Météorique |
| Silver / Gold / Tin / Copper | Argent / Or / Étain / Cuivre |
| Electrum / Electrotine / Blue Alloy | Électrum / Electrotine / Alliage bleu |
| Magnesium / Magnesium Chloride | Magnésium / Chlorure de Magnésium |
| Titanium Tetrachloride | Tétrachlorure de Titane |
| Sodium / Sodium Sulfate | Sodium / Sulfate de Sodium |
| Chlorine / Fluorine / Oxygen / Hydrogen / Nitrogen | Chlore / Fluor / Oxygène / Hydrogène / Azote |
| Helium / Carbon / Sulfur / Phosphorus | Helium / Carbone / Soufre / Phosphore |
| Silicon | Silicium |
| Mercury | Mercure |
| Sulfuric / Nitric / Hydrochloric / Hydrofluoric Acid | Acide Sulfurique / Nitrique / Chlorhydrique / Fluorhydrique |
| Ammonia / Nitric Oxide / Nitrogen Dioxide | Ammoniac / Oxyde Nitrique / Dioxyde d'Azote |
| Tetranitromethane / Ethenone | Tétranitrométhane / Éthénone |
| Diesel / Bio Diesel / Cetane-Boosted Diesel | Diesel / Bio Diesel / Diesel boosté de Cétanes |
| Naphtha / Benzene / Ethylene / Butadiene / Styrene | Naphte / Benzène / Éthylène / Butadiène / Styrène |
| Methane / Methanol / Ethanol / Chloromethane / Chloroform | Méthane / Méthanol / Éthanol / Chlorométhane / Chloroforme |
| Dimethyldichlorosilane / Polydimethylsiloxane | Diméthyldichlorosilane / Polydiméthylsiloxane |
| Silicone Rubber | Gomme de Silicone |
| Styrene-Butadiene Rubber (raw) | Gomme de Styrène-Butadiène (brute) |
| Polyethylene / Polystyrene | Polyéthylène / Polystyrène |
| Tetrafluoroethylene / Polytetrafluoroethylene (PTFE) | Tétrafluoroéthylène / Polytétrafluoroéthylène (PTFE) |
| Cryolite / Fluorite / Lepidolite / Mica / Biotite | Cryolite / Fluorite / Lépidolite / Mica / Biotite |
| Apatite / Tricalcium Phosphate | Apatite / Phosphate Tricalcique |
| Saltpeter / Salt / Salt Water | Salpêtre / Sel / Eau Salée |
| Borosilicate Glass | Verre Borosilicate |
| Ruby / Sapphire / Green Sapphire | Rubis / Saphir / Saphir vert |
| Nichrome | Nichrome |
| Glowstone / Soul Sand / Lava / Ashes | Pierre lumineuse / Sable des Âmes / Lave / Cendres |
| Endstone | Pierre de l'End |
| Ender Eye / Ender Pearl | Oeil de l'Ender / Perle de l'Ender |
| UU-Matter / UU-Amplifier | Matière-UU / Amplificateur-UU (UUM / UUA) |
| Steam | Vapeur |

---

## 5. Autres mods (noms en jeu, en anglais)

| Nom en jeu | Mod |
|---|---|
| Vibrant Crystal, Vibrant Alloy, Energetic Alloy, Conductive Iron, Soularium | EnderIO |
| Capacitor Bank, Vibrant Capacitor Bank, Double-Layer Capacitor | EnderIO |
| Nutrient Distillation, The Vat, Crafter, Soul Binder, Soul Vial | EnderIO |
| Killer Joe, Experience Obelisk, Powered Spawner, Inventory Panel | EnderIO |
| Farming Station, Wireless Charger, Ender Fluid Conduit | EnderIO |
| World Anchor, Personal Anchor, Passive Anchor | Chicken Chunks / Railcraft |
| Personal Space (portail) | PersonalSpace |

Concepts à traduire : « dimension personnelle », « portail », « monde vide », « monde superplat ».

---

## 6. Expressions récurrentes du livre de quêtes

| Anglais | Français |
|---|---|
| Now that you have X, you can… | Maintenant que vous avez X, vous pouvez… |
| To proceed you will need… | Pour progresser, il vous faudra… |
| Make one of them. / Go and craft one. | Fabriquez-en un. |
| …hold X in your hand to skip this quest. | …tenez X en main pour passer cette quête. |
| Hold 128 sheets to skip this questline. | Tenez 128 feuilles en main pour passer ce chapitre. |
| You only need to complete one of the tasks. | Vous n'avez besoin d'accomplir qu'une seule des tâches. |
| As usual… | Comme d'habitude… |
| BTW | Au passage / D'ailleurs |
| Check NEI / look around in NEI | Consultez NEI / fouillez un peu dans NEI |
| Check out the X tab for more info. | Consultez l'onglet X pour plus d'informations. |
| You're Gonna Hate This | Vous allez détester ça |
