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

---

## 7. Termes fixés lors de la traduction des tiers MV → UMV et Endgame

Classés par chapitre où ils apparaissent pour la première fois. Rappel : un nom laissé en anglais l'est parce qu'il s'affiche ainsi dans NEI.

### MV

| Anglais | Français | Remarque |
|---|---|---|
| Solar Grade Silicon / Silicon Solar Grade | Silicium de grade Photovoltaïque | nom GT en jeu (S:Material.siliconsolargrade, sans « (Poly SI) » dans le texte) |
| Raw Silicon / Silicon (matériau GT) | Silicium brut | S:Material.silicon=Silicium brut |
| Silicon Dioxide | Dioxyde de Silicium | matériau GT |
| Silicon Tetrachloride | Tétrachlorure de Silicium | matériau GT |
| Trichlorosilane | Trichlorosilane | matériau GT |
| Seed Oil / Fish Oil | Huile Végétale / Huile de Poisson | matériaux GT |
| Glycerol | Glycérol | matériau GT |
| Acetic Acid | Acide acétique | matériau GT (minuscule en jeu) |
| Sodium Hydroxide | Hydroxyde de Sodium | matériau GT |
| Sodium Persulfate / Sodium Bisulfate | Persulfate de Sodium / Bisulfate de Sodium | matériaux GT |
| Iron (III) Chloride | Chlorure de Fer III | matériau GT |
| Vinyl Chloride / Polyvinyl Chloride | Chlorure de Vinyle / Chlorure de Polyvinyle | matériaux GT ; PVC reste PVC |
| Polycaprolactam | Polycaprolactame | matériau GT |
| Molten Polyethylene | Polyéthylène en fusion |  |
| Fermented Biomass / Biomass | Biomasse fermentée / Biomasse |  |
| Red Garnet / Red Granite | Grenat rouge / Granite rouge | matériaux GT |
| Brown / Yellow Limonite | Limonite brune / Limonite Jaune | matériaux GT |
| Cassiterite Sand | Sable de Cassitérite | matériau GT |
| Tantalum / Tantalite / Niobium | Tantale / Tantalite / Niobium | matériaux GT |
| Manganese / Spessartine / Pyrolusite | Manganèse / Spessartine / Pyrolusite | matériaux GT |
| Magnetic Steel | Acier Magnétique | matériau GT (steelmagnetic) |
| Vanadiumsteel / Damascus Steel | Acier au Vanadium / Acier Damas | matériaux GT |
| Black Steel | Acier noir | matériau GT |
| Shadow Metal | Métal de l'Ombre | matériau GT |
| Brass | Laiton | matériau GT |
| Flint / Diamond / Tungsten | Silex / Diamant / Tungstène | matériaux GT |
| Distilled Water | Eau distillée |  |
| MV Superconductor Base | Base de Supraconducteur MV | matériau GT ; superconductor = supraconducteur |
| Dark Steel | Dark Steel | EnderIO, reste en anglais (comme Vibrant Alloy) |
| Hootch / Fire Water / Nutrient Distillation | Hootch / Fire Water / Nutrient Distillation | fluides EnderIO, anglais en jeu |
| Soul Vial, Yeta Wrench, Conduit Probe, Painting Machine, Fused Quartz, Quite Clear Glass, Reinforced Obsidian | (inchangés) | EnderIO, anglais en jeu |
| Translocator | Translocateur | traduit en jeu (Translocator mod) |
| Plantball / Plant Mass / Bio Chaff | (inchangés) | objets, anglais en jeu |
| Coolant (IC2) | Coolant | gardé en anglais (nom de fluide) |
| facade / hardened facade | façade / façade renforcée | concept EnderIO (objet : Conduit Facade) |
| chunkloader / Passive/Personal/World Anchor | chunkloader / (inchangés) | Railcraft, anglais en jeu |
| cover (GT) | cover | « un cover Needs Maintenance », « Vent cover » |
| coil(s) (EBF) | bobine(s) | « bobines en Kanthal » |
| You're Gonna Hate This in MV Too #N | Vous allez détester ça en MV aussi #N | série de titres |
| oredict | oredict | non traduit |
| wire cutters | pince coupante |  |
| crowbar | pied-de-biche |  |

### EV

| Anglais | Français | Remarque |
|---|---|---|
| Graphene | Graphène | matériau GT |
| Advanced Glue | Colle avancée | matériau GT |
| Polyvinyl Acetate / Vinyl Acetate | Acétate de Polyvinyle / Acétate de Vinyle | matériaux GT |
| Methyl Acetate | Acétate de Méthyle | matériau GT |
| Hypochlorous Acid | Acide Hypochloreux | matériau GT |
| Epoxid | Époxy | matériau GT (les objets « Epoxid Board/Sheet » restent en anglais) |
| Epichlorohydrin / Bisphenol A / Phenol | Épichlorhydrine / Bisphénol A / Phénol | matériaux GT |
| Iron(III) Chloride / Sodium Persulfate | Chlorure de Fer III / Persulfate de Sodium | matériaux GT |
| Sodium Sulfide | Sulfure de Sodium | matériau GT |
| Dichlorobenzene / Polyphenylene Sulfide | Dichlorobenzène / Sulfure de Polyphénylène | matériaux GT |
| Tungsten / Tungsten Trioxide / Tungstate / Scheelite | Tungstène / Trioxyde de Tungstène / Tungstate / Scheelite | matériaux GT |
| Uranium 238 / Plutonium 239 | Uranium 238 / Plutonium 239 | noms GT |
| Galena / Lead | Galène / Plomb | matériaux GT |
| Blue Steel / Black Steel / Brass / Rose Gold | Acier bleu / Acier noir / Laiton / Or Rose | matériaux GT |
| Meteoric Steel | Acier Météorique | matériau GT |
| Boron | Bore | matériau GT |
| Calcium Chloride / Ammonium Chloride | Chlorure de Calcium / Chlorure d'Ammonium | matériaux GT |
| Platinum Residue / Platinum Salt / Refined Platinum Salt / Reprecipitated Platinum | Résidus de Platine / Sel de Platine / Sel de Platine raffiné / Platine Reprécipité | matériaux GT |
| Palladium Enriched Ammonia | Ammoniac enrichi au Palladium | matériau GT |
| Aqua Regia | Aqua Regia | nom GT non traduit (« l'eau régale » en glose) |
| Niobium-Titanium | Niobium-Titane | matériau GT |
| Uraniumtriplatinide | Base de Supraconducteur EV | nom NEI du matériau |
| Heavy Fuel / Wood Tar / Isopropylbenzene | Fioul lourd / Goudron de Bois / Isopropylbenzène | matériaux GT |
| Platline | ligne du Platine | concept |
| Platinum Processing, Step N | Traitement du Platine, étape N | titres de quête |
| Dimensional Goal: X | Objectif dimensionnel : X | déjà utilisé en HV |
| debuff | malus |  |
| Radiation (debuff) | Radiation | nom de l'effet, majuscule |
| drum (Extra Utilities) | Drum / fût | l'objet reste « Drum », « fût » en texte courant |
| to decay (radium) | se désintégrer / désintégration |  |
| Lead-Lined Box, Decay Warehouse, Magnum Torch, Quantum Eye, Data Orb, Water Reservoir, Reservoir Hatch, Quadruple Input Hatch | (inchangés) | objets/machines, anglais |
| superconductor (SC) | supraconducteur (SC) | déjà utilisé en HV |
| Quantum Chest / Quantum Tank / Super Chest / Super Tank | (inchangés) | machines GT |

### IV

| Anglais | Français | Remarque |
|---|---|---|
| Callisto / Europa / Ceres / Mercury / Venus / Io | Callisto / Europe / Cérès / Mercure / Vénus / Io | astres, noms français usuels |
| X Trip | Voyage sur X | titres de quête |
| Callisto Ice | Glace de Callisto | matériau GT |
| Naquadah Oxide Mixture (NOM) | Mixture d'oxyde de Naquadah (NOM) | matériau GT |
| Silicon Solar Grade | Silicium de grade Photovoltaïque | matériau GT |
| Gallium Arsenide | Arséniure de Gallium | matériau GT |
| Yttrium Barium Cuprate | Cuprate d'Yttrium Baryum | matériau GT |
| Vanadiumtriindinide | Base de Supraconducteur IV | nom NEI du matériau |
| Nitration Mixture | Mixture de Nitration | matériau GT |
| 2-Nitrochlorobenzene / Chlorobenzene | 2-Nitrochlorobenzène / Chlorobenzène | matériaux GT |
| Diphenyl Isophtalate | Isophtalate de diphényle | matériau GT |
| Phthalic Acid / Dimethylbenzene | Acide Phtalique / Diméthylbenzène |  |
| Potassium Dichromate / Potassium Nitrate / Potassium Disulfate | Dichromate de Potassium / Nitrate de Potassium / Disulfate de Potassium | matériaux GT |
| Chromium Trioxide / Chromium Dioxide | Trioxyde de Chrome / Dioxyde de Chrome | matériaux GT |
| Leach Residue / Rarest Metal Residue | Résidus de lixiviation / Résidus de Métaux les plus Rares | matériaux GT |
| Rhodium Sulfate (Solution) / Rhodium Salt (Solution) / Rhodium Nitrate / Rhodium Filter Cake | Sulfate de Rhodium (Solution de) / Sel de Rhodium (Solution de Sels de) / Nitrate de Rhodium / Gâteau de filtration du Rhodium | matériaux GT |
| Rhodium-Plated Palladium | Palladium plaqué Rhodium | matériau GT |
| Sodium Ruthenate / Ruthenium Tetroxide (Solution) / Hot Ruthenium Tetroxide Solution | Ruthénate de Sodium / Tétroxyde de Ruthénium (Solution de) / Solution chaude de Tétroxyde de Ruthénium | matériaux GT |
| Acidic Osmium/Iridium Solution | Solution acide d'Osmium / d'Iridium | matériaux GT |
| Iridium Dioxide / Iridium Chloride | Dioxyde d'Iridium / Chlorure d'Iridium | matériaux GT |
| Palladium Salt / Palladium Metallic Powder / Reprecipitated Palladium | Sel de Palladium / Poudre Métallique de Palladium / Palladium Reprécipité | matériaux GT (NEI affiche « Précipité de Palladium » pour le matériau ; texte gardé cohérent avec Platine Reprécipité) |
| Formic Acid / Sodium Formate / Sodium Nitrate | Acide Formique / Formiate de Sodium / Nitrate de Sodium | matériaux GT |
| Oxalic Acid | Oxalic Acid | non traduit en jeu, garder l'anglais |
| Cerium / Cerium Dioxide / Cerium Chloride / Cerium Oxalate | Cérium / Dioxyde de Cérium / Chlorure de Cérium / Oxalate de Cérium | matériaux GT |
| Hafnium / Hafnia / Zirconia / Hafnia-Zirconia Blend / Low-Purity Hafnium / Hafnium Runoff | Hafnium / Hafnia / Zircone / Mélange Hafnia-Zirconia / Hafnium de faible pureté / Rinçage de Hafnium | matériaux GT |
| Zirconium Tetrachloride | Tétrachlorure de Zirconium | matériau GT |
| Iodine / Seaweed Ash | Iode / Cendres d'Algues | matériaux GT |
| Monazite Sulfate (Diluted) / Ammonium Nitrate | Sulfate de Monazite (dilué) / Nitrate d'Ammonium | matériaux GT |
| Thorium-Phosphate / Uranium Filtrate / Thorianite | Phosphate de Thorium / Filtrat d'Uranium / Thorianite | matériaux GT |
| Europium III Oxide | Oxyde d'Europium III | matériau GT |
| Samarium / Magnetic Samarium / Samarium Ore Concentrate / Muddy Samarium Rare Earth Solution | Samarium / Samarium Magnétique / Concentré de minerai de Samarium / Solution boueuse de Terres Rares Samarium | matériaux GT |
| Lanthanum / Lanthanum Chloride | Lanthane / Lanthanum Chloride | le chlorure n'est pas traduit en jeu |
| Thorium Nitrate / Thorium Hydroxide / Thorium Tetrafluoride / Thorium 232 | Nitrates de Thorium / Hydroxyde de Thorium / Tétrafluorure de Thorium / Thorium 232 | matériaux GT |
| Zinc Chloride / Zinc Sulfate | Chlorure de Zinc / Sulfate de Zinc | matériaux GT |
| Infused Gold / Deep Iron / Firestone | Or infusé / Deep Iron / Firestone | noms NEI |
| Soldering Alloy | alliage à souder | matériau GT « Alliage à Souder » |
| Leach / leached | lixivier / lixivié |  |
| to sift / sifting | tamiser / tamisage |  |
| Lanthanide processing | traitement des Lanthanides |  |

### LuV

| Anglais | Français | Remarque |
|---|---|---|
| imprint (CAL) | empreinte | « faire une empreinte » ; l'objet garde son nom NEI (Circuit Imprint). |
| Speed Upgrade / Ender Quarry | Speed Upgrade / Ender Quarry | Extra Utilities, en anglais dans NEI. |
| Netherite Scrap, Hot/Brittle Netherite Scrap, Netherite Scrap Seed, Netherite Nanoparticles, Intensely Bonded Netherite Nanoparticles, Dense Netherite Plate | (inchangé) | Objets en anglais dans NEI. |
| Rich/Poor Nether Waste, Nether Semifluid, Nether Air, Nefarious Gas/Oil, Heavy Hellish Mud, Hellish Metal, Netherrack Froth, Milled Netherrack | (inchangé) | Fluides/matériaux non traduits en jeu. |
| Netherite line / Naquadah line | chaîne du Netherite / chaîne du Naquadah | « line » de traitement = chaîne. |
| froth | mousse | Produit de la Flotation Cell. |
| milling balls | billes de broyage | Isamill. |
| Boron Plasma / Helium Plasma | Plasma de Bore / Plasma d'Helium | Nom de matériau GT (Bore, Helium). |
| superconductor | supraconducteur | Titre « Supraconducteurs LuV ». |
| Naquadah coils | bobines en Naquadah | Idem « bobines en Trinium ». |
| Rare Earth (I/II/III) | Terres Rares (I/II/III) | Suivant le glossaire (Terres Rares). |
| Flawed / Exquisite (gemme) | ébréchée / Exquise | Qualités de gemme. |
| antimony trichloride solution | solution de trichlorure d'antimoine | Pas de clé GT ; nom générique en minuscules. |
| Waste Water | eaux usées | Cité entre « ». |
| Mk1/MkII Fusion Reactor | Fusion Reactor Mk1 / MKII | Nom de machine en anglais. |
| Grade 1 Purified Water | Eau purifiée de grade 1 |  |
| Super Glue / Ethyl Cyanoacrylate | Super Glue / Ethyl Cyanoacrylate | Pas de clé GT FR. |

### ZPM

| Anglais | Français | Remarque |
|---|---|---|
| wormhole | trou de ver | Quêtes du « savant » (Final Goal) et Wormhole Generator. |
| Prismarine line | chaîne de la Prismarine | Prismarine = matériau GT (même nom). |
| Prismatic Naquadah / Prismatic Acid / Prismatic Gas / Prismatic Crystal / Prismarine Solution / Prismarine Precipitate | (inchangé) | Noms non traduits en jeu. |
| foil | feuille fine | « feuille fine de Plomb » ; les objets nommés (Netherite Foil, Naquarite Universal Insulator Foil) restent en anglais. |
| binding powder | poudre liante |  |
| Enriched Naquadah | Naquadah enrichi | Clé GT naquadahenriched. |
| Black Plutonium | Plutonium noir | Clé GT. |
| Proteus / Triton / Enceladus / Oberon | Protée / Triton / Encelade / Obéron | Noms français des lunes. |
| Disproportionation | Dismutation | Terme de chimie. |
| parameters (TecTech) | paramètres | Parameter Hatch reste en anglais. |
| Uncertainty status / Power Switch | État d'incertitude / Interrupteur | Interface des multiblocs TT. |
| Laser Hatch / Source Hatch / Target Hatch | (inchangé) | Source = sortie, Target = entrée. |
| Strontium Oxide / Strontium Hydroxide / Nitrobenzene | (inchangé) | Valeurs restées en anglais dans GregTech_fr_FR.lang. |

### UV

| Anglais | Français | Remarque |
|---|---|---|
| Superconductors (titre de quête) | Supraconducteurs | Comme en HV : « Supraconducteurs UV (524,288 EU/t) ». |
| Endgame | fin de partie | « Bienvenue en fin de partie ! » |
| computation | computation | Terme TecTech conservé (computation/s). |
| computer rack | computer rack | Objet TecTech, reste en anglais ; « rack » au pluriel « racks ». |
| vents (QC) | ventilations | Composants dissipant la chaleur dans les racks. |
| overclock / overvolt (QC) | overclock / overvolt | Paramètres du QC, non traduits. |
| slice (multibloc) | tranche | « le QC se construit en une série de tranches ». |
| Schrödinger Matrix | matrice de Schrödinger | Concept de l'Uncertainty Resolver. |
| hatch | hatch (féminin) | « une Energy Hatch », « une hatch de transmission ». |
| Raw Growth Catalyst Medium / Raw Growth Medium | Milieu catalytique de croissance brut | Nom GT FR (growthmediumraw). |
| Sterilized Growth (Catalyst) Medium | Milieu catalytique de croissance stérilisé | Nom GT FR = « Milieu catalytique de croissance » ; « stérilisé » ajouté pour la clarté. |
| Pile of Neutrons | Amas de neutrons cosmiques | Nom Avaritia FR. |
| Cosmic Neutronium | Neutronium Cosmique | Nom GT FR. |
| Garnet Sand / Red Garnet / Yellow Garnet | Sable de Grenat / Grenat rouge / Grenat jaune | Noms GT FR ; « Garnet » (filon) → Grenat. |
| Nether Star | Étoile du Nether | Nom GT FR. |
| Metastable Oganesson | Oganesson métastable | Nom GT FR. |
| Cerium-doped Lutetium Aluminium Garnet (Ce:LuAG) | Grenat d'Aluminium Lutétium dopé au Cérium (Ce:LuAG) | Nom GT FR ; gemmes « de LuAG », « exquises ». |
| Extracting Nano Resin / Chlorinated Rare Earth Concentrate | (anglais) | Noms GTNH Lanthanides non traduits en jeu. |
| Nano Tech | nanotech | « Bénie soit la nanotech ». |
| Mince Meat | viande hachée (Mince Meat) | Nom d'objet anglais rappelé entre parenthèses. |
| Bacteria (fluide) | bactéries (Bacteria) |  |
| culture / DNA Sample / Data Orb / Plasmid | culture / DNA Sample / Data Orb / Plasmid | Objets BartWorks, restent en anglais. |
| Kuiper Belt / Pluto | ceinture de Kuiper / Pluton | Noms de lieux traduits (comme Lune). |
| Circuits, Assemble! | Circuits, rassemblement ! | Clin d'œil « Avengers, rassemblement ! ». |

### UHV

| Anglais | Français | Remarque |
|---|---|---|
| Infinity | Infinité | Nom GT FR (matériau). |
| Infinity Catalyst | Catalyseur d'Infinité | Nom GT FR. |
| Raw Bio Medium | Médium de biocatalyseur brut | Nom GT FR (biomediumraw). |
| Awakened Draconium | Draconium éveillé | Nom GT FR (matériau) ; les « Awakened Draconium Coils » restent en anglais. |
| Lanthanum / Caesium / Cerium | Lanthane / Caesium / Cérium | Noms GT FR. |
| Xenoxene | Xenoxène | Nom GT FR ; la culture « Xenoxene Xenoxsis » reste en anglais. |
| Dire Crafting Table | Établi de Dire | Nom Avaritia FR (DCT conservé comme sigle). |
| Neutron Collector | Collecteur de neutrons | Nom Avaritia FR (bloc Avaritia, à distinguer du Neutronium Compressor GT qui reste en anglais). |
| Mutated Living Solder | Mutated Living Solder | Nom GT resté en anglais ; « living solder » générique → soudure vivante. |
| Seaweed / Unknown Crystal / Barnarda C Sapling | (anglais) | Objets GalaxySpace non traduits en jeu. |
| Living Crystal Chip | Living Crystal Chip | Nom d'objet GT. |
| stargate | stargate (féminin) | « la stargate », « SG ». |
| The Final Frontier | L'ultime frontière | Référence Star Trek (titre FR du film V). |
| Harder, Better, Faster, Stronger | (anglais) | Titre de chanson conservé ; « Pt 1 » → « partie 1 ». |

### UEV

| Anglais | Français | Remarque |
|---|---|---|
| Infinity (matériau) | Infinité | Nom GT en jeu (S:Material.infinity) ; « Infinity Coil » reste en anglais (nom de bloc) |
| Infinity Helmet / Breastplate / Pants / Boots | Casque / Plastron / Jambières / Bottes de l'infinité | Noms Avaritia FR en jeu (NEI) |
| World Breaker / Planet Eater / Nature's Ruin / Sword of the Cosmos / Longbow of the Heavens | Destructeur de mondes / Avaleur de planète / Ravageur de nature / Epée du cosmos / Arc long des paradis | Noms Avaritia FR en jeu (NEI, « Epée » sans accent comme en jeu) |
| Eternal Singularity | Singularité éternelle | Nom Eternal Singularity FR en jeu |
| Spacetime | Espace-Temps | Nom GT en jeu (matériau) |
| Mehen Belt | Ceinture de Mehen | Nom Amun-Ra en jeu |
| Raw Tengam / Attuned Tengam | Tengam brut / Tengam Harmonisé | Noms GT en jeu |
| optical circuits | circuits optiques | Gammes nommées : circuits Crystal, Wetware, Bioware, Bio (nom de gamme en anglais) |
| Package (NAC™ : Fundamentals, Advanced Routing, Crystal, Automation, Optical, Assembling, Wetware and Bioware, Premium) | Pack Essentiels, Pack Routage avancé, Pack Cristal, Pack Automatisation, Pack Optique, Pack Assemblage, Pack Wetware et Bioware, Pack Premium | Noms « commerciaux » humoristiques des quêtes, pas des noms NEI ; les modules (Nanopart Splitter, Etching Array…) restent en anglais |
| owner's manual | manuel d'utilisation | Pastiche publicitaire NAC™ |
| coil (heating coil, générique) | bobine | « 2112 blocs de bobines » ; noms de blocs en anglais |
| excited catalyst (DTPF) | catalyseur excité | Générique |
| My Eyes Hurt! | J'ai mal aux yeux ! | Série de titres (#1 à #4) |
| You Know the Drill | Vous connaissez la chanson | Titre récurrent (UEV, UIV pt.2) |
| perfect overclock | overclock parfait |  |

### UIV

| Anglais | Français | Remarque |
|---|---|---|
| Godforge / Forge of the Gods | la Godforge / la Forge of the Gods (« la Forge ») | Nom de multibloc en anglais, féminin |
| Graviton Shard | Graviton Shard | Nom GT en jeu, resté en anglais |
| Quark Gluon Plasma | Plasma Gluon de Quarks dégénérés | Nom GT en jeu |
| Transcendent Metal | Métal Transcendant | Nom GT en jeu |
| Proto-Halkonite Steel | Proto-Halkonite Steel | Nom GT en jeu (anglais) |
| Liquid Helium | Hélium liquide | Nom GT en jeu |
| Energised Tesseract | Energised Tesseract | Nom NEI (orthographe britannique conservée) |
| neutron star | étoile à neutrons | Générique |
| black hole / event horizon / Hawking radiation | trou noir / horizon des événements / rayonnement de Hawking | Générique |
| QoL (Quality of Life) | confort (QoL) | « objets de confort (QoL) » |
| Crayon and Melon | Crayon et Melon | Jeu de mots sur Creon/Mellion, conservé tel quel |

### UMV

| Anglais | Français | Remarque |
|---|---|---|
| SpaceTime / Spacetime (matériau) | Espace-Temps | Matériau GT (S:Material.spacetime) ; « poudre d'Espace-Temps » |
| Eternity (matériau) | Éternité | Matériau GT ; Eternity Blocks → blocs d'Éternité |
| White Dwarf Matter | Matière de Naine Blanche | Casse NEI conservée |
| Black Dwarf Matter | Matière de naine noire | Casse NEI conservée (différente de la naine blanche) |
| Magnetohydrodynamically Constrained Star Matter (MHDCSM) | Matière Stellaire soumise à des contraintes magnétohydrodynamiques (MHDCSM) | Nom NEI ; sigle MHDCSM conservé |
| Raw Stellar Plasma | Plasma Stellaire brut | Nom FR non confirmé en jeu (seul « Mixture condensée de Plasma Stellaire brut » existe) |
| Stellar Catalyst | Catalyseur stellaire | NEI : « Catalyseur stellaire dimensionnellement transcendant » |
| Redstone Plasma | Plasma de Redstone |  |
| Infinity Wire | fil d'Infinité | Matériau Infinity = Infinité |
| Universium / Shirabon / Hexanite / Ichorium / Magmatter / Creon / Mellion / Hypogen | (inchangés) | Identiques en FR |
| Spacetime Compression / Time Dilation / Stabilisation Field Generator (+ tiers Crude, Primitive, Stable, Advanced, Superb, Exotic, Perfect, Tipler, Gallifreyan) | (inchangés) | Casings TecTech en anglais ; titres « T4: Advanced » etc. gardés |
| casing(s) | casing(s) | Gardé tel quel (« vos casings ») |
| energy hatch / laser hatch (générique) | energy hatch / laser hatch | Féminin : « une energy hatch » |
| wireless (hatch, energy) | sans fil | « energy hatches sans fil », « mode sans fil » |
| parallels | parallèles | « 64 parallèles » |
| pity system | système de pitié |  |
| power positive | rentable en énergie |  |
| Subspace Cooling | Subspace Cooling (titre : Refroidissement subspatial) | Nom d'option en jeu |
| Wireless Computation / Cloud Computation (Server/Client) Hatch | calcul sans fil / Cloud Computation (Server/Client) Hatch |  |
| yield | rendement |  |
| batch (EoH) | lot | « par lot réussi » |

### Endgame

| Anglais | Français | Remarque |
|---|---|---|
| Endgame Goals (nom de la questline) | Objectifs de fin de partie | Traduit à la demande ; la référence dans Tier 12 - UMV (21tDEYpt…) suit |
| Stargate (Ring Block, Base, Chevron, Chevron Block, Command) | Stargate … | Objets en anglais ; « la stargate » (féminin) en texte courant |
| Planck-Scale Circuits / Planck-Scale Manifolds | (inchangés) | Objets |
| Yocto Power IC / Infinite Wafer / Magmatter Nanites | (inchangés) | Objets |
| Astral Array (Fabricator) | (inchangé) |  |
| run (partie) / Group Run | partie / partie de groupe | Noms propres de runs (Ballers Run, Bee Run, Cell Run 2) gardés |
| XOR quests | quêtes XOR |  |
| questbook completion | complétion du livre de quêtes |  |
| to dial (stargate) | composer |  |
