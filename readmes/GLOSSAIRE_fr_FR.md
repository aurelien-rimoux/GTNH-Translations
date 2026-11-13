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


---

## 8. Termes fixés lors de la traduction du reste du livre

Classés par chapitre de première apparition.

### Début de partie, Se nourrir

| Anglais | Français | Remarque |
|---|---|---|
| Feeding Yourself (nom de la questline) | Se nourrir | table du brief |
| offhand (slot) | main secondaire | Backhand |
| lootbag / to uptier a lootbag | sac de butin / améliorer (le tier d') un sac de butin |  |
| Fortune / Looting (enchantements) | Fortune / Butin | noms vanilla FR |
| Holo Glasses | Lunettes Holographiques | nom NEI FR |
| Part Builder, Crafting Station, Seared Tank, Drain, Drying Rack, Mattock, Scythe, Punji Stick, Ball of Moss | (inchangés) | Tinker's Construct, anglais en jeu |
| Bound Leather / Woven Cotton / Tanned Leather | (inchangés) | anglais en jeu |
| Lunch Bag / Lunch Box / Food Journal | (inchangés) | Spice of Life, anglais en jeu |
| Digger's Backpack / Miner's Backpack | (inchangés) | Forestry, anglais en jeu |
| Sleeping Bag | Sleeping Bag | OpenBlocks, anglais en jeu |
| Ore Finder Wand / Magnetic Iron Rod | (inchangés) | noms d'objets |
| Vending Machine / Coke Oven / Coke Oven Hatch | (inchangés) | machines GT ; « une hatch » |
| Rainforest Oak / Sacred Oak / Paperbark | (inchangés) | arbres, anglais en jeu |
| GT tools : Screwdriver, Wrench, Crowbar, Wire Cutter, Soft Mallet, Hammer, Plunger, Butchery Knife | (inchangés) + glose FR (tournevis, clé, pied-de-biche, pince coupante, maillet souple, marteau, ventouse) | noms NEI anglais |
| Pam's : Saucepan / Pot / Skillet / Mixing Bowl / Cutting Board / Juicer / Bakeware | Casserole / Marmite / Poêle / Jatte / Planche à découper / Presse-fruits / Moule à gâteaux | noms NEI FR |
| Grain / Fruit / Veggie / Fish Bait | Appât aux céréales / aux fruits / aux légumes / au poisson | noms NEI FR (titres traduits) |
| Animal Trap / Fish Trap | (inchangés) | anglais en jeu |
| Cooking for Blockheads : Kitchen Floor, Counter, Cabinet, Fridge, Sink, Tool Rack, Cooking Table, Toaster | Sol de cuisine, Comptoir, Armoire, Frigidaire, Évier, Porte-outils, Table de cuisine, Grille-pain | noms NEI FR |
| Wheaty Juice / Korn / Doppelkorn / Vodka / Rum / Flowing Spirit / Malformed Slush / Uncooked Slush / Dezil's Marshmallow / Glowing Marshmallow | (inchangés) | anglais en jeu |
| Talisman of Nourishment | (inchangé) | Thaumic Exploration |
| effets : Slowness / Haste / Blindness / Hunger / Weakness / Nausea / Paralysis | Lenteur / Célérité / Cécité / Faim / Faiblesse / Nausée / Paralysie |  |
| hotbar | barre d'action |  |
| shank (de faim) | cuisse | « demi-cuisse de faim » |
| to backport | rétroporter |  |

### Tier 0.5 - Vapeur

| Anglais | Français | Remarque |
|---|---|---|
| boiler (générique) | chaudière | féminin ; noms de machines en anglais (Simple/Advanced Solar Boiler, Lava Boiler…), « la Simple Solar Boiler » |
| steam machine | machine à vapeur | les machines gardent leur nom NEI (Steam Macerator, Steam Extractor, Steam Forge Hammer, Steam Compressor, Steam Furnace, Alloy Smelter) |
| Macerator (Steam) | Macerator / Steam Macerator | corrige l'ancien « Broyeur » (NEI : Steam Macerator) |
| Bricked Blast Furnace | Bricked Blast Furnace | corrige l'ancien « Haut Fourneau en Briques » |
| Upgrade: X (titres) | Amélioration : X | série de titres du chapitre Vapeur |
| tank (générique) | réservoir | objets nommés en anglais (Iron Tank, Water Tank, ULV Tank) ; « réservoir Buildcraft » |
| buffer (steam) | réserve | « réserve de vapeur » |
| to calcify / calcification | s'entartrer / entartrage | chaudières solaires |
| output port | port de sortie |  |
| mold | moule | « moule à pépites » ; shapes (Extruder) = formes |
| Flint and Steel | Briquet | nom vanilla FR |
| Dolly (JABBA) | Diable | nom JABBA FR en jeu |
| Ball of Moss | Balle de Mousse | nom Tinkers FR en jeu |
| Reinforcement (Tinkers) | Renfort | nom Tinkers FR ; le modificateur reste « Reinforced » |
| Hammer / Lumber Axe / Excavator / Scythe / Tool Forge / Tool Station / Crafting Station / Smeltery / Casting Basin | (inchangés) | Tinkers, anglais en jeu |
| Obzinite | Obzinite | matériau Tinkers GTNH, anglais |
| Cast Iron | Cast Iron | S:Material.castiron non traduit |
| Glow Flower | Fleur brillante | nom Natura FR |
| Bloodwood / Fusewood / Darkwood / Ghostwood | (inchangés) | Natura, anglais en jeu |
| Steeleaf / Ironwood (matériaux) | Feuilleacier / Bois de Fer | noms GT FR |
| hazmat suit | combinaison hazmat | casse IC2 FR (minuscule) |
| lootbag Basic / Steam | sac de butin Basic / Steam | noms de types laissés en anglais |
| Stockroom Catalog / Typesetting Table / Printing Press / Clipboard / Trash Can / Upgrade Template / Name Remover / Scuba Helmet / Plunger | (inchangés) | anglais en jeu |
| wire cutter | pince coupante | déjà au glossaire MV, rappel |
| pigman / zombie pigman | cochon-zombie | Vampire Pigman (Infernal/Witchery) gardé en anglais |
| "... is So Old School" (série de titres) | « ..., c'est dépassé » | Tinkers (Hammer, Lumber Axe, Excavator, Scythe) |

### Tier 1 - LV

| Anglais | Français | Remarque |
|---|---|---|
| Handle Resources Like a Bo$$ #N | Gérez vos ressources comme un Bo$$ #N | série de titres (Bo$$ conservé) |
| Handle Tiny Piles Like a K1ng | Gérez les petits tas comme un K1ng | titre, K1ng conservé |
| You're Gonna Hate This #N (LV) | Vous allez détester ça #N | série de titres (cf. « en MV aussi ») |
| Cobalt Brass | Cobalt Laiton | nom GT en jeu (S:Material.cobaltbrass), tel quel |
| Redstone Alloy / Red Alloy | Alliage de Redstone / Alliage Rouge | matériaux GT |
| Sulfuric Light Fuel / Sulfuric Heavy Fuel / Sulfuric Naphtha / Sulfuric Gas | Fioul Léger Sulfuré / Fioul Lourd Sulfuré / Naphta Sulfuré / Gaz Sulfurique | noms GT en jeu (les titres déjà traduits « Fioul sulfurique léger/lourd » sont conservés) |
| Naphtha / LPG / Refinery Gas | Naphte / GPL / Gaz de Raffinerie | noms GT en jeu |
| Refined Glue (GT « Glue ») | Colle affinée | S:Material.glue ; « glue » générique = colle |
| Heavy Oil / Oilsands | Pétrole Lourd / Sables Bitumineux | noms GT en jeu |
| Soapstone / Fullers Earth / Rock Salt | Pierre à Savon / Terre à foulon / Sel Gemme | noms GT en jeu |
| Tetrahedrite / Stibnite / Antimony / Cinnabar / Realgar | Tétrahédrite / Stibnite / Antimoine / Cinabre / Realgar | noms GT en jeu |
| Magnesite / Quicklime / Magnesia | Magnésite / Chaux Vive / Magnésie | noms GT en jeu |
| Diamond Dolly | Diable en diamant | nom JABBA FR en jeu ; « dolly » générique = diable |
| squid ink | encre de calmar |  |
| node (Transfer Node, ExU) | node | « les nodes » ; objets Transfer Node / Transfer Pipe / World Interaction Upgrade (WIU) en anglais |
| Long Distance Fluid/Item Pipeline (LDFP/LDIP) | pipeline de fluides/d'objets longue distance | bloc en anglais, titre traduit |
| cobble / stone (vanilla) | pierre taillée / roche |  |
| Seismic Prospector | Seismic Prospector | machine GT, « prospecteur » en texte courant |

### La révolution verte

| Anglais | Français | Remarque |
|---|---|---|
| The Green Revolution (nom de la questline) | La révolution verte | Table du brief |
| crop | culture | « vos cultures », « une culture CropsNH » |
| crop stick(s) / double crop stick | Crop Stick(s) / double Crop Stick | Objet CropsNH, anglais en jeu |
| seed | graine | « graine 31/31/31 » (le texte déjà FR de Sticky Canes dit « semence », toléré) |
| to breed / breeding / crossbreeding | croiser / obtenir (une nouvelle espèce) / croisement | « croisement déterministe », « croisement par pool » |
| deterministic breeding / mutation | croisement déterministe / mutation déterministe |  |
| pool (breeding/mutation pool) | pool (féminin) | « pool de mutation », « les pools partagées » ; noms de pools (Food, Reed, Root, Danger) en anglais |
| offspring | descendance / descendant |  |
| stats (Growth / Gain / Resistance) | stats (Growth / Gain / Resistance) | Noms de stats en anglais comme dans l'infobulle ; « résistance » en texte courant |
| to stat up / statting | améliorer les stats / amélioration des stats |  |
| maxed (stats) | aux stats maximales |  |
| Nutrient Score / Nutrient Points | score de nutriments / points de nutriments |  |
| weeds | mauvaises herbes |  |
| sickness / sick crop / diseases | maladie / culture malade / maladies |  |
| sub-soil / undersoil | sous-sol / bloc de sous-sol | Bloc placé sous la terre de la culture |
| biome tag | tag de biome |  |
| humidity | humidité |  |
| Spade / Reinforced Spade / Plant Lens / Portable Scanner / Plant Cure / Weed-EX / Fertilizer / Enriched Fertilizer | (inchangés) | Objets/fluides CropsNH/GT, anglais en jeu |
| Crop Manager / Crop Breeder / Seed Generator / Crop Gene Extractor / Crop Synthesizer | (inchangés) | Machines, anglais |
| Industrial Farm (IF) / Seed Bed | Industrial Farm (IF, féminin) / Seed Bed | Multibloc et casing, anglais |
| Environmental Enhancement Unit / Environmental Module / Advanced Harvesting Unit / Fertilization Unit / Growth Acceleration Unit / Overclocked Growth Acceleration Unit | (inchangés, féminin « la … Unit ») | Améliorations de l'IF ; titres « L'Advanced Harvesting Unit », « La Fertilization Unit » |
| Lily / Lilies / Lilium | Lily / Lilies / Lilium | Noms d'espèces en anglais ; titres « Lilies de Marbre », « Lilies de Sable des Âmes »… |
| Oreberries | oreberries | Nom de catégorie de cultures conservé ; titres « Baies de Fer », « Baies de Cuivre »… |
| crop species names (Auronia, Stickreed, Withereed, Tearstalks, Nightshade, Star Wart, Gaia Wart…) | (inchangés) | Lang CropsNH entièrement en anglais |
| X leaves will 4x your Y ore | les feuilles de X multiplient par 4 le rendement de votre minerai de Y | Formule récurrente |
| Tools of the Trade N | Les outils du métier N | Série de titres |
| Bonsai | bonsaï | « Bonsaï de chêne », « Bonsaï d'acajou » (jungle) |
| farmhand | garçon de ferme |  |
| Crop Stats / Crop Nutrients (titres) | Stats des cultures / Nutriments des cultures | Référencés dans « Titrage des mutations » |
| Environmental Preferences (titre) | Préférences environnementales | Référencé dans « Nutriments des cultures » |
| B**s / B**keepers (censure de Bees/Beekeepers) | A*****s / A*****teurs | Censure adaptée (Abeilles / Apiculteurs) |

### Se déplacer / sans mourir

| Anglais | Français | Remarque |
|---|---|---|
| Getting Around... | Se déplacer... | nom de la questline (table du brief) |
| ...Without Dying | ...sans mourir | nom de la questline (table du brief) |
| jetpack | jetpack | invariable en texte courant ; noms d'objets en anglais (Electric Jetpack, Advanced Electric Jetpack) |
| Coal Jetpack / Copterpack | Jetpack à charbon / Pack hélicoptère | noms FR en jeu (Adventure Backpack) |
| Piston Boots | Bottes à piston | nom FR en jeu (Adventure Backpack) |
| Inflatable Boat | Canot pneumatique | nom FR en jeu (Adventure Backpack) |
| Hose (Adventure Backpack) | Flexible | nom FR en jeu |
| Adventure Backpack | Adventure Backpack | nom en jeu ; variantes : sac à dos Cochon / Pigman / Vache / Ocelot / Dragon (skins FR en jeu) |
| Flippers | Palmes | nom FR en jeu (Biomes O' Plenty) |
| hover mode | mode stationnaire | jetpacks |
| mode-switch key (IC2) | touche de changement de mode d'IC2 |  |
| Hang Glider / glider | Hang Glider / planeur | objet OpenBlocks en anglais ; « planeur » en texte courant |
| Elevator / Rotating Elevator | (inchangés) | OpenBlocks, anglais en jeu ; « ascenseur » en texte courant |
| Travel Anchor / Staff of Traveling | (inchangés) | EnderIO ; « ancre » en texte courant |
| minecart / cart | wagonnet | Railcraft ; noms d'objets (Steam/Electric Locomotive, Fluid Loader…) en anglais |
| track(s) (booster, high speed, reinforced, electric, wye, switch, junction, locking) | rails (d'accélération, à grande vitesse, renforcés, électriques, en Y, d'aiguillage, de jonction, de verrouillage) | texte courant ; noms NEI anglais (Electric Track) |
| furnace cart | wagonnet motorisé (Furnace Cart) |  |
| Turret Base / turret | Turret Base / tourelle | OMT, objets en anglais |
| Protect Your Base: Tier N | Protégez votre base : Tier N | série de titres |
| bolt / crossbow limb / fletching | carreau / branche d'arbalète / empennage | Tinkers ; « fletching » laissé tel quel pour la recherche NEI |
| spear / arrowhead | lance / pointe de flèche |  |
| nano armor / quantum armor / nanosuit | armure nano / armure quantique / nanosuit | texte courant ; objets IC2 en anglais (QuantumSuit Bodyarmor, GraviChestPlate) |
| Boots of the Traveller (+ Electric/Nanosuit/Quantum) / Boots of the Voidwalker | (inchangés) | noms en jeu en anglais |
| Goggles of Revealing | (inchangé) | Thaumcraft, anglais en jeu |
| Thaumostatic Harness / Thaumostatic Pylon | (inchangés) | Thaumcraft/Automagy |
| Aer / Potentia / Volatus (aspects) | (inchangés) | noms d'aspects affichés en latin |
| Ironwood / Knightmetal (armures TF) | (inchangés) | objets TF en anglais ; Steeleaf = Feuilleacier (FR en jeu) |
| Sash (Botania) | écharpe ; Soujourner's / Globetrotter's / Planestrider's Sash inchangés | noms Botania en anglais |
| Compressed Steel / Desh / Titanium Armor | Armure en Acier / Desh / Titane compressé | titres |
| step assist / jump boost / speed boost | assistance à la marche / bonus de saut / bonus de vitesse |  |
| Charm of Dislocation / Chaos Locator / Teleporter / Telepad / Teleposer | (inchangés) | noms en jeu |

### De meilleures bases, Forestry

| Anglais | Français | Remarque |
|---|---|---|
| Building Better Bases (questline) | De meilleures bases | nom d'onglet fixé par le brief |
| Forestry and Multifarms (questline) | Forestry et Multifarms | nom d'onglet fixé par le brief |
| Builder's Wand (Stone/Iron/Diamond/Unbreakable) | Baguette en pierre / en fer / en diamant / incassable | noms BBW traduits en jeu ; titres « Baguette de bas niveau / de niveau intermédiaire / de haut niveau » |
| Forge Microblocks saw (Iron/Diamond) | Scie en fer / Scie en diamant | noms Forge Multipart traduits en jeu |
| Ztones Flat Lamp | Lampe Plate | nom Ztones en jeu (titre « Lampes Plates ») |
| Carpenter's Blocks (blocs) | blocs façonnables (Porte de garage façonnable, Trappe façonnable, Plaque de pression façonnable…) | noms traduits en jeu ; le nom du mod reste Carpenter's Blocks |
| Catwalks (blocs) | Passerelle, Échafaudage (de bâtisseur), Échelle à cage, Colonne de soutien, Rails (de propulsion) robuste, Chalumeau, Ruban d'avertissement, Corde lumineuse | noms Catwalks traduits en jeu |
| ArchitectureCraft Sawbench | Banc de sciage | nom traduit en jeu |
| Soldering Iron (Forestry) | Fer à Souder | nom Forestry traduit en jeu |
| Electron Tube (+ Copper/Tin/…/Ender) | Electron Tube | Forestry, anglais en jeu ; titres « Electron Tubes : Copper, Tin, Bronze » |
| Farm Block / Farm Hatch / Farm Valve / Farm Control / Farm Gearbox | (inchangés) | Forestry, anglais en jeu ; « une Farm Hatch » (féminin) |
| Carpenter, Thermionic Fabricator, Fermenter, Still, Squeezer, Centrifuge, Rainmaker, Treealyzer, Spectacles, Grafter, Proven Grafter | (inchangés) | machines/objets Forestry, anglais en jeu ; « la Centrifuge » de Forestry |
| Peat / Bituminous Peat / Ash / Mulch / Fertilizer / Fruit Juice / Honey Drop / Honeydew | (inchangés) | objets/fluides Forestry, anglais en jeu |
| Iodine Capsule / Phosphoric Iodine Capsule / Dissipation Charge | (inchangés) | objets Forestry |
| Sturdy Casing (« Forestry Core Block ») | boîtier robuste (Sturdy Casing) ; titre « Bloc central de Forestry » |  |
| Tree species (Silver Lime, Hill Cherry, Teak, Balsa, Apple Oak, Silver Birch, Dark Oak, Jungle, Acacia…) | (inchangés) | espèces Forestry/Extra Trees, anglais en jeu ; titres de quête = nom d'espèce, non sortis |
| Tree traits Faster / Fastest / Higher / High / Sappiness | maturation Faster / Fastest, rendement Higher / High, Sappiness | valeurs d'allèles anglaises en jeu ; « Fertilité élevée », « Sappiness élevée » en texte |
| to breed (trees) / breeding / pure species | croiser / croisement / race pure |  |
| germling / sapling | jeune pousse / pousse |  |
| X Get! | X : obtenu(e)(s) ! | mème conservé |
| Botany items (Iron Trowel, Soil Meter, Weedkiller, Mortar, Ceramic Block/Tile, Ash/Pulp/Mulch/Sulphur/Fertilizer/Compost Powder) | (inchangés) | Binnie, anglais en jeu |
| Tileworker / Glassworker / Panelworker / Woodworker / Master Carpentry Hammer / Glass Fittings | (inchangés) | Binnie Extra Trees, anglais en jeu |
| Seared Stone / Seared Bricks / Rough Brownstone / Smeltery | (inchangés) | Tinkers' Construct, anglais en jeu |
| Crystalline Pink Slime | Slime rose cristallin | matériau GT |
| chisel (outil générique) / to chisel | ciseau / ciseler | l'objet Chisel reste « Chisel » ; Auto Chisel inchangé |
| Shulker Box (Iron/Gold/…), X Barrel, X Chest | (inchangés) | noms d'objets ; « Peut être teinte ! » |

### Objectifs multiblocs

| Anglais | Français | Remarque |
|---|---|---|
| Multiblock Goals | Objectifs multiblocs | nom de la questline (table du brief) |
| X Coil Upgrade (titres) | Bobines en X | ex. « Bobines en Nichrome », « Bobines en Électrum fluxé », « Bobines en Infinité » ; « More Heat - Kanthal Coil Upgrade » → « Plus de chaleur - bobines en Kanthal » |
| Electrum Flux | Électrum fluxé | matériau GT (S:Material.electrumflux) |
| X Glass (titres, verre Borosilicate) | Verre X | « Verre IV », « Verre UMV » ; « Better Glass Upgrade, EV Glass » → « Meilleur verre : verre EV » |
| Borosilicate glass tier: Titanium/Tungstensteel/... (N) | verre Borosilicate en Titane (4), Acier au Tungstène (5)… | noms de matériaux GT FR ; Transcendent → Métal Transcendant |
| firebox (Railcraft) | chambre de combustion | nom FR en jeu « Chambre de combustion pour chaudière à combustible… » ; la Firebox GT (Large Boiler) reste « Firebox » |
| Low/High Pressure Boiler Tank | (inchangé) | Railcraft, anglais dans NEI ; « réservoir de chaudière » en texte courant |
| Water Tank Siding | (inchangé) | Railcraft, anglais dans NEI |
| smeltery / faucet / casting table / casting basin | smeltery / robinet (faucet) / table de moulage / bassin de moulage | Tinkers' Construct ; smeltery reste anglais (NEI) |
| Seared Brick (objet) | brique fumée | nom TConstruct FR en jeu ; le bloc « Seared Bricks » reste anglais |
| Powderbarrel | baril de poudre |  |
| Duct Tape | Duct Tape | objet GT, anglais |
| soldering iron / soft mallet / hammer / wrench / screwdriver | fer à souder / maillet souple / marteau / clé / tournevis | outils génériques ; messages de maintenance (« Pipe is loose. »…) gardés en anglais (GUI) |
| survival autoplace | survival autoplace | nom de la fonction, gardé |
| MSHP (Multiblock Structure Hologram Projector) | (inchangé) |  |
| focusing (QFT) | focalisation | « focalisé au Neptunium / au Fermium » |
| skip (QFT) | raccourci | « raccourci de la chaîne du Naquadah », « raccourci des stem cells » |
| Shielding / Manipulating (titres QFT) | Blindage / Manipulation de tier N |  |
| beam / Particle / Energy / Focus / Amount | faisceau / Particle / Energy / Focus / Amount | propriétés affichées en jeu gardées en anglais ; « l'Amount » |
| coolant (LINAC/Synchrotron) | liquide de refroidissement | le fluide IC2 « Coolant » reste Coolant |
| Algae / Green / Brown / Golden-Brown / Red Algae | (inchangés) ; « algues » en générique | objets GT++ anglais en jeu |
| Drones are not Drones! | Les drones ne sont pas des faux bourdons ! | jeu de mots drone / faux bourdon (abeille mâle) |
| Sievert (Sv) | Sieverts (sv) |  |
| NKE (Neutron Kinetic Energy) | NKE (énergie cinétique des neutrons) |  |

### Traitement de masse, EU

| Anglais | Français | Remarque |
|---|---|---|
| singleblock | monobloc | « son équivalent monobloc », « les machines monoblocs » |
| parallels per voltage tier | parallèles par palier de tension | formule récurrente des multis GT++ |
| speed boost / speed bonus | bonus de vitesse | « un bonus de vitesse de 3x » |
| EU discount | réduction d'EU | « une réduction d'EU de 25%% » |
| Item Pipe Casing / pipe casing | Item Pipe Casing / pipe casing | blocs, restent en anglais ; « par tier d'Item Pipe Casing » |
| glass tier | tier du verre | « Le tier du verre n'a pas d'importance » |
| solenoid (tier) | solénoïde | « par tier de solénoïde » ; bloc Solenoid Coil en anglais |
| multi-amp hatch | hatch multi-amp | comme dans les tiers (féminin) |
| exotic energy hatch | exotic energy hatch | TecTech, anglais |
| Mega (multis) | Megas | « les Megas de certaines machines » |
| slice (Advanced Assembly Line) | tranche | comme le QC ; état [warn]STUCK[/warn] gardé, glosé « bloquée » |
| laser overclock | laser overclock | terme de l'infobulle, conservé |
| imperfect overclock | overclock imparfait | pendant de « overclock parfait » |
| wraps (CAL) | « wraps » | objets Wrap of X, anglais |
| Steam Age | âge de la Vapeur |  |
| Steam multiblocks (Steam Separator, Steam Squasher, Steam Grinder, Steam Blender, Steam Fuser, Steam Presser, Steam Purifier) | (inchangés) | machines, anglais ; « multiblocs à vapeur » en texte courant |
| Mass Processing (concept) | traitement de masse | nom de l'onglet : Traitement de masse |
| Storing and Transforming EU | Stocker et transformer les EU | nom de l'onglet |
| Kerosene | Kérosène | pas de clé GT trouvée, nom français usuel |
| Biocatalyzed Propulsion Fluid | Biocatalyzed Propulsion Fluid | nom GT FR resté en anglais |
| Cryotheum / Pyrotheum | Cryotheum / Pyrothéum | noms GT FR |
| Growth Catalyst | Milieu catalytique de croissance | glossaire UV |
| containment block (EIC) | bloc de confinement | « bloc de Neutronium / d'Infinité / de Métal Transcendant / d'Espace-Temps / d'Universium » |
| battery hull | battery hull | objet GT, anglais ; « petits battery hulls » |
| Battery Buffer | Battery Buffer / buffer | machine GT, anglais |
| single-use / rechargeable battery | batterie à usage unique / rechargeable | titres « Batterie à usage unique : Mercure », « Batterie réutilisable : Sodium » |
| transformer (générique) | transformateur | les machines gardent leur nom (Low Voltage Transformer, Power Transformer, Hi-Amp) |
| step-up / step-down | élévateur / abaisseur | « mode élévateur (step-up) » |
| soft mallet | maillet en caoutchouc (soft mallet) |  |
| LESU casings | LESU casings |  |
| capacitor (LSC, Tesla) | condensateur | les objets Lapotronic Capacitor restent en anglais |
| Primary Tesla Windings / Tesla Coil Covers / transceivers | (inchangés) | Tesla Tower, anglais |
| wireless EU network | réseau d'EU sans fil |  |
| dam (Hydro Dam) | barrage | machine « Hydro Dam » en anglais |
| Power Goggles | Power Goggles (« les lunettes ») | objet, anglais |
| clickbait | putaclic |  |

### Produire de l'énergie

| Anglais | Français | Remarque |
|---|---|---|
| How to Generate Power (questline) | Produire de l'énergie | nom imposé par le brief |
| multi (multiblock) | multibloc |  |
| powergen / power generation | production d'énergie |  |
| optimal flow (rate) | débit optimal | turbines |
| fuel efficiency | rendement du carburant |  |
| Overflow Efficiency tier | tier d'Overflow Efficiency | libellé d'infobulle conservé |
| Loose Mode | mode Loose | option de turbine XL |
| XL Turbines | turbines XL | noms de machines (XL Steam/Gas/Plasma Turbine) en anglais |
| spreadsheet | tableur | Large Turbine Calculator / GTNH Power Planner gardés en anglais |
| Superheated Steam / SH Steam / SC Steam | vapeur surchauffée / vapeur SH / vapeur SC | « vapeur surchauffée » déjà utilisé ailleurs |
| Hot Coolant / Solar Salt (Hot/Cold) / Super Coolant / IC2 Coolant | (inchangés) | anglais en jeu (GT/GT++) ; « Solar Salt froid » |
| Liquid Hydrogen | Liquid Hydrogen | non traduit en jeu |
| High Octane Gasoline (HOG) | Essence à indice d'octane élevé (HOG) | matériau GT |
| Light Fuel | Carburant léger | matériau GT |
| Creosote | Créosote | matériau GT (féminin) |
| Liquid Air | Air liquide | matériau GT |
| Combustion Promoter | Combustion Promoter | non traduit en jeu |
| Tachyon Rich Temporal Fluid / Spatially Enlarged Fluid | (inchangés) | non traduits en jeu |
| Molten X (booster/stabilisant) | X en fusion | « Caesium en fusion », « Uranium 235 en fusion », « Base de Supraconducteur UIV en fusion » |
| Atomic Separation Catalyst | Catalyseur de séparation atomique | matériau GT |
| X Plasma (Tin, Neon, Krypton, Americium, Force, Runite, Astral Titanium, Celestial Tungsten) | Plasma d'Étain / de Néon / de Krypton / d'Américium / de Force / de Runite / d'Astral Titanium / de Celestial Tungsten | « Plasma de » + nom GT FR (Astral Titanium, Celestial Tungsten, Runite restent en anglais en jeu) |
| Advanced Nitinol / Titansteel / Arcanite / Dragonblood | (inchangés) | noms GT en jeu |
| Naquadah Based Fuel MkI…MkVI | Combustible liquide à base de Naquadah MkI…MkVI | nom NEI ; « (Appauvri) » pour depleted |
| Nuclear Based Fuel (Th/U/Pu) | Combustible nucléaire (Th/U/Pu) | titres ; NEI : Combustible Liquide à base de Thorium/d'Uranium/de Plutonium |
| Semi-Stable Antimatter | Antimatière semi-stable | Antimatter = Antimatière (GT) ; Protomatter reste en anglais |
| Arcane Furnace (Thaumcraft) | Infernal Furnace | nom affiché en jeu |
| Railcraft Liquid Boilers | chaudières à combustible liquide de Railcraft | nom FR Railcraft |
| Power of the Sun at X Level / 1x1 X | La puissance du soleil au niveau X / 1x1 X | titres de série |
| Kinetic Wind / Water Power X | Énergie éolienne / hydraulique cinétique X | titres de série |
| Portable Clean Energy X / Pocket Plasma X / Geothermal Power X | Énergie propre portable X / Plasma de poche X / Énergie géothermique X | titres de série |
| Toss Your Magic Junk in Here X | Jetez votre bric-à-brac magique ici X | titres de série |
| Absorbing Magic Energy to Produce EU X | Absorber l'énergie magique pour produire des EU X | titres de série |
| Standard / Tricky / Alternate / Obscenely Dangerous Nuclear Fuel | Combustible nucléaire standard / délicat / alternatif / obscènement dangereux | titres |
| Tier N Coil (Naquadah Fuel Refinery) | Bobine de tier N | titres |
| fusion chain (mk1/mk2/mk3) | chaîne de fusion (mk1/mk2/mk3) | « réacteur mk1 », « un compact » (Compact Fusion Reactor) |
| bottleneck | goulot d'étranglement |  |
| penalty (XL Plasma) | pénalité |  |
| fuel value | valeur énergétique |  |
| breeder reactor | réacteur surgénérateur |  |
| Essentia / aspects Thaumcraft (Potentia, Ignis, Auram, Arbor, Aer, Lucrum, Praecantatio) | essentia + nom latin | aspects non traduits en jeu |
| Compressed Solar (Double…Septuple) / Essentia Generator: X / Radioisotope Thermoelectric Generator / Turbine Housing | (inchangés) | titres = noms d'objets/machines |

### Pétrole, Automatisation

| Anglais | Français | Remarque |
|---|---|---|
| Working with Oil | Travailler le pétrole | nom de questline (table du brief) |
| Basic Automation | Automatisation de base | nom de questline (table du brief) |
| Oil (matériau) | Pétrole | S:Material.oil ; Heavy Oil = Pétrole Lourd |
| Heavy Fuel | Fioul lourd | nom GT en jeu |
| Sulfuric Light Fuel / Sulfuric Gas | Fioul Léger Sulfuré / Gaz Sulfurique | noms GT en jeu |
| Refinery Gas | Gaz de Raffinerie | S:Material.gas |
| Raw Gasoline / Gasoline | Essence Brute / Essence | noms GT en jeu |
| Nitrous Oxide | Oxyde Nitreux | nom GT ; « nitro » en texte courant |
| Oilsands | Sables Bitumineux | nom GT |
| LPG | GPL | nom GT |
| Anti-Knock Agent | Anti-Knock Agent (agent antidétonant) | pas de nom FR en jeu |
| MTBE Reaction Mixture | MTBE Reaction Mixture | nom GT non traduit |
| Solid Super Fuel / Magic Solid Super Fuel | (inchangés) | objets ; « super carburant » en texte courant |
| Superheated Steam | vapeur surchauffée | déjà utilisé dans Power |
| Loose mode (turbine) | mode Loose | déjà utilisé dans Power |
| cracking / hydro-cracking / steam-cracking | craquage / hydrocraquage / vapocraquage | lightly/moderately/severely = légèrement/modérément/fortement |
| Oil Cracker | Oil Cracking Unit | nom de la machine (titres « Craqueur… » existants conservés) |
| Oil Drilling Rig / Oil Rig | Oil Drilling Rig / rig | machine |
| Dangote Distillus / Mega Distillation Tower / Chemical Plant | (inchangés) | machines |
| Large Boiler (Titanium/Tungstensteel) | Large Boiler (féminin : « la Titanium Boiler ») | chaudière |
| oil baron | baron du pétrole |  |
| fluid voiding | destruction des fluides |  |
| cart (Steve's Carts) | wagonnet | « Modules de wagonnet : … » pour les titres |
| Cart Assembler, Coal Engine, Basic Farmer, Basic Wood Cutter, Side Chests, Cargo Manager, External Distributor, Advanced Detector Rail | (inchangés) | Steve's Carts, anglais en jeu |
| hull (Steve's Carts) | coque (hull) |  |
| chip (ProjectRed) | puce | noms d'objets (Item Responder Chip, Item Broadcaster Chip, Item Stock Keeper Chip, Item Extractor Chip, Crafting Chip…) en anglais |
| Routed Interface/Junction/Request Pipe | tuyau d'interface / de jonction / de requête | noms d'objets en anglais dans NEI |
| blacklist | liste noire |  |
| overflow (storage) | stockage par défaut (overflow) / débordement |  |
| Drawer Controller | Drawer Controller | Storage Drawers, anglais en jeu ; drawers = tiroirs |

### La bio pour tous

| Anglais | Français | Remarque |
|---|---|---|
| Bio for the Masses | La bio pour tous | nom de la questline (table du brief) |
| powergen | production d'énergie |  |
| renewable | renouvelable | « énergie renouvelable » |
| Charcoal | Charbon de Bois | matériau GT (S:Material.charcoal) |
| Coal / Lignite Coal | Charbon / Charbon de Lignite | matériaux GT |
| Coal Coke | Coal Coke | objet Railcraft, anglais en jeu |
| Carbon Monoxide | Monoxyde de Carbone | matériau GT |
| Carbon Dioxide | Dioxyde de Carbone | matériau GT |
| Creosote (Oil) | Créosote | matériau GT |
| Lubricant | Lubrifiant | matériau GT |
| Biodiesel | Bio Diesel | nom GT en jeu (S:Material.biodiesel) |
| Wood Vinegar / Wood Gas / Charcoal Byproducts | Vinaigre de Bois / Gaz de Bois / Sous-produits du Charbon de Bois | matériaux GT |
| Toluene / Acetone / Raw Gasoline | Toluène / Acétone / Essence Brute | matériaux GT |
| Nitrobenzene | Nitrobenzene | pas de clé GT FR, gardé en anglais |
| Industrial TNT (iTNT) | Industrial TNT (iTNT) | objet IC2, anglais en jeu |
| Solid Super Fuel / Magic Solid Super Fuel / Super Fuel | (inchangés) | objets, SSF / MSSF |
| Fuel Binder / Magic Fuel Binder | (inchangés) ; « liant » / « liant magique » en texte courant |  |
| Alumentum | Alumentum | Thaumcraft, anglais en jeu |
| Sugar Beet / Sugar Cane / Canola / Goldfish / Oil Berry / Stickreed / Tearstalks / Fertilia | (inchangés) | cultures CropsNH, anglais en jeu |
| Sacred Oak / Redwood / Rainforest Oak | (inchangés) | arbres, anglais en jeu |
| Lumber Axe | Lumber Axe | Tinkers' Construct, anglais en jeu |
| sapling | pousse |  |
| cropsticks | Crop Sticks | nom d'objet CropsNH |
| crop stats / high-statted | statistiques des cultures / à hautes statistiques |  |
| DT / DTing | DT (féminin, « la DT ») / distiller en DT | Distillation Tower |
| Pyro | Pyro | abréviation du Pyrolyse Oven |
| Chemplant / Exxonmobil Chemical Plant | Chemplant / ExxonMobil Chemical Plant (féminin) | multibloc GT++ |
| optimal flow | débit optimal | turbines |
| fuel value / heat value | pouvoir calorifique |  |
| wallshare | partager les murs | chaudières collées |
| fish trap / Fish Catcher | piège à poissons / Fish Catcher |  |
| fertilizer (générique) | engrais |  |

### Physique nucléaire

| Anglais | Français | Remarque |
|---|---|---|
| Powerful Nuclear Physics | Physique nucléaire | nom de la questline (table du brief) |
| nuke / fluid nuke / vacuum nuke / vac nuke / wrench nuke | nuke / fluid nuke / vacuum nuke / vac nuke / wrench nuke | jargon conservé, féminin (« une fluid nuke ») ; titres des quêtes-objets gardés (Fluid Nukes, Vacuum Nukes) |
| breeding / breeder reactor / to breed X into Y | surgénération / réacteur surgénérateur / transformer X en Y par surgénération |  |
| fuel rod / depleted rod / single, dual, quad rod | barre de combustible / barre usée / barre simple, double, quadruple | les objets nommés (Empty Fuel Rod, Excited Uranium Fuel Rods…) restent en anglais |
| chamber (IC2 reactor) | chambre |  |
| heat-neutral (setup) | thermiquement neutre |  |
| Superheated Steam / Supercritical Steam | vapeur surchauffée / vapeur supercritique | Steam = Vapeur ; Hot Coolant reste en anglais (IC2 Hot Coolant en jeu) |
| molten salt / molten salt reactor | sel fondu / réacteur à sels fondus |  |
| T Salt / U Salt / TB Salt / LFTR Fuel 1-3 / LFTR Fuel Base / Fuel 1-3 | (inchangés) | noms d'objets/fluides GT++ en anglais |
| Fuel Refinery (Reactor Fuel Processing Plant, RFPP), Reactor Processing Unit, Cold Trap, Sparge Tower | (inchangés) | machines ; « raffinerie » toléré en reprise |
| sparging | barbotage | « le barbotage des sels » |
| Lithium Fluoride / Beryllium Fluoride / Zirconium Tetrafluoride / Uranium Hexafluoride | (inchangés) | valeurs GT restées en anglais ; Thorium Tetrafluoride = Tétrafluorure de Thorium (clé GT) |
| Lutetium / Americium / Deuterium | Lutétium / Américium / Deutérium | noms GT FR |
| Helium-3 | Helium-3 | nom GT |
| Tin / Bismuth / Zinc / Force / Runite Plasma | Plasma d'Étain / de Bismuth / de Zinc / de Force / de Runite |  |
| Thorium/Uranium/Plutonium Based Liquid Fuel (Excited State) | (inchangés) | noms GoodGenerator en anglais ; « Excited Thorium/Uranium/Plutonium » gardé tel quel |
| Celestial Tungsten / Astral Titanium / Advanced Nitinol / Cryotheum | (inchangés) | noms GT en anglais |
| The Core / High Density (HDU, HDP) / Excited (rods) | (inchangés) | noms de barres |
| boosters / coolants (Naquadah Reactor additives) | boosters / refroidissants |  |
| latch (redstone) | verrou (latch) |  |
| Max Danger Nukes | Nukes au danger maximal | titre de quête, aussi cité en [quest] dans MOX Nukes |

### Course à l'espace

| Anglais | Français | Remarque |
|---|---|---|
| Space Race (questline) | Course à l'espace | nom imposé par le brief |
| rocket / Tier N rocket | fusée / fusée de tier N | objets restent « Tier N Rocket » ; titres « Rocket Tier N » gardés en anglais |
| rocket fuel (générique) | carburant pour fusée | les fluides GT++ gardent leur nom NEI (RP-1 Rocket Fuel, Dense Hydrazine Rocket Fuel, CN3H7O3 / H8N4C2O4 Rocket Fuel) |
| (Green) / (Purple) Rocket Fuel | H8N4C2O4 Rocket Fuel (vert) / CN3H7O3 Rocket Fuel (violet) | couleur traduite entre parenthèses |
| launch pad | pas de tir | le bloc reste « Rocket Launch Pad » |
| dungeon (Galacticraft) | donjon | « Donjon lunaire », « Donjon martien », « Donjon de Cérès / d'Io / d'Encelade / de Protée / de Pluton » |
| Boss Monster | Boss |  |
| schematic | schéma | objets « NASA Workbench Schematic », « Shuttle Schematic » en anglais |
| fuel canister | réservoir de carburant | objets « Small/Medium/Large/Extra Large Fuel Canister » en anglais |
| oxygen tank (générique) | réservoir d'oxygène | objets « Light/Medium/Heavy/Super Heavy/Ultra Heavy Oxygen Tank » en anglais |
| airlock | sas | objets « Air Lock Frame / Air Lock Controller » en anglais |
| space station | station spatiale |  |
| Mothership | vaisseau mère | nom Amun-Ra FR |
| Mothership Navigation Console | Console de navigation de vaisseau mère | nom Amun-Ra FR en jeu |
| Rocket Engine Jet / Rocket Engine Base | Moteur de fusée à réaction / Socle de moteur de fusée | noms Amun-Ra FR en jeu ; Ion Thruster Jet/Base restent en anglais |
| Artificial Gravity Generator | Générateur de gravité artificielle | nom Amun-Ra FR en jeu ; Artificial Gravity Disruptor reste en anglais |
| Raw Tengam Ore | minerai de Tengam brut | matériau GT « Tengam brut » |
| Basic Wafer / Advanced Wafer | (inchangés) | Galacticraft, anglais en jeu ; titres « Galettes » corrigés en « Wafers » / « Advanced Wafers » |
| Coal Tar, Coal Tar Oil, Kerosene, Anthracene, Naphthalene, Ethylbenzene, Formaldehyde, Hydrazine, Monomethylhydrazine, 1,1-Dimethylhydrazine, Nitrogen Tetroxide, Hydrogen Peroxide, 2-Ethylanthraquinone, 2-Ethylanthrahydroquinone, Phthalic Anhydride | (inchangés) | fluides GT++ non traduits en jeu |
| Thermal Padding | Thermal Padding | objet, anglais en jeu ; « vêtements thermiques » en texte courant |
| oxidizer | comburant |  |

### SFM, tuyaux, Kami

| Anglais | Français | Remarque |
|---|---|---|
| SFM and Computers | SFM et ordinateurs | nom de questline (table du brief) |
| Handle Logistics with Pipes | Logistique par tuyaux | nom de questline (table du brief) |
| OpenComputers items (Computer Case, Power Converter, Disk Drive, Adapter, Keyboard, Screen, Microchip, Control Unit, Card Base, Network Card, Hard Disk Drive, Floppy Disk, Memory, Graphics Card) | (inchangés) | anglais dans le lang FR d'OC ; texte courant : disque dur, mémoire, carte graphique |
| SFM blocks (Machine Inventory Manager/MIM, Inventory Cable, Cable Cluster, Item Valve, Block Gate, Redstone Emitter/Receiver, Manager Duplicator, Factory Labeler, RF Node) | (inchangés) | anglais dans le lang FR de SFM / Steve's Addons |
| workflow (SFM) | workflow | terme de l'interface SFM, non traduit |
| Logistics Pipes items (Unrouted Transport Pipe, Basic Logistics Pipe, Logistics Chassis MkN, Logistics Request Table, Logistics Power Junction, Satellite Logistics Pipe, Remote Orderer, upgrades) | (inchangés) | anglais dans le lang FR de LP |
| pipe (LP, générique) | tuyau | « Basic Logistics Pipe » reste en anglais |
| module (LP) / crafting module / ItemSink module / Provider module | module / module de fabrication / module ItemSink / module Provider |  |
| upgrade (LP, générique) | amélioration | noms d'objets (Fluid Crafting Upgrade…) en anglais |
| chassis | chassis | invariable, nom de l'objet |
| buffer (inventaire/réservoir) | tampon |  |
| default route (LP) | route par défaut |  |
| junction (pipes) | jonction |  |
| Red Alloy | Alliage Rouge | matériau GT |
| Unleashed the Power - X | Libérer le pouvoir - X | série de titres (Kami) |
| Unbreakable X | X incassable | série de titres (Kami) |
| Ichor / Ichorium / Ichorcloth | Ichor / Ichorium / Ichorcloth | Thaumic Tinkerer, anglais en jeu |
| Warp (Thaumcraft) | Warp | non traduit (usage déjà présent dans le livre) |
| essentia | essentia (féminin) | « fondre en essentia » |
| Shadowmetal | Métal de l'Ombre | matériau GT (glossaire MV) |
| wand caps / wand core | embouts / cœur de baguette |  |
| Alchemical Furnace / Large Essentia Smeltery / Essentia Diffusion Cell | (inchangés) | noms d'objets/machines |

### Applied Energistics

| Anglais | Français | Remarque |
|---|---|---|
| ME network / ME system | réseau ME / système ME |  |
| channel(s) (AE2) | canal / canaux | « 8 canaux », « canaux P2P » |
| subnet / subnetwork | sous-réseau |  |
| crafting CPU | CPU de fabrication | multibloc AE2 |
| co-processing / co-processor | co-traitement / co-processeur | les blocs restent « Co-Processing Unit » (anglais en jeu) |
| pattern / crafting pattern / processing pattern | pattern / pattern de fabrication / pattern de traitement | objets « Blank Pattern », « Encoded Pattern » en anglais |
| autocrafting | autocrafting | conservé (déjà utilisé ailleurs) |
| storage cell / storage component (générique) | cellule de stockage / composant de stockage | noms NEI : « 1k ME Storage Cell », « 1k ME Storage Component » (anglais) |
| bytes | octets |  |
| smart / dense / glass / covered cable (générique) | câble intelligent / dense / en verre / couvert | objets NEI : ME Smart Cable, ME Dense Smart Cable… (anglais) |
| fluix cable (générique) | câble fluix |  |
| ME Controller | Contrôleur ME | NEI FR |
| ME Drive / ME Chest | Lecteur ME / Coffre ME | NEI FR |
| Energy Acceptor / Energy Cell / Dense Energy Cell | Accepteur d'énergie / Cellule d'énergie / Grande cellule d'énergie | NEI FR |
| Charger | Chargeur | NEI FR |
| Crystal Growth Accelerator | Accélérateur de croissance cristalline | NEI FR (la Crystal Growth Chamber reste en anglais) |
| ME Security Terminal | Terminal de sécurité ME | NEI FR |
| Wireless Terminal / Wireless Booster | Terminal sans-fil / Booster sans-fil | NEI FR (ME Wireless Access Point reste en anglais) |
| ME Import / Export / Storage Bus | Bus d'import ME / Bus d'export ME / Bus de Stockage ME | NEI FR |
| Matter Condenser | Condenseur de matière | NEI FR |
| Quantum Ring | Anneau quantique ME | NEI FR (ME Quantum Link Chamber reste en anglais) |
| Tiny TNT | Petite TNT | NEI FR |
| Crafting Monitor (bloc) | Moniteur de fabrication | NEI FR |
| ME Interface | ME Interface | forme part (NEI) ; le bloc s'affiche « Interface ME » ; usage déjà établi dans le livre |
| Dual Interface | Interface ME double | AE2FC, NEI FR |
| Fluid Storage Bus / Fluid Import Bus / Fluid Export Bus | Bus de stockage ME de fluide / Bus ME d'import de Fluides / Bus ME d'export de Fluides | AE2FC, NEI FR |
| Fluid Storage Cell Nk / Fluid Component Nk | Cellule ME Nk de stockage de fluide / Composant ME Nk de stockage fluide | AE2FC, NEI FR (titres de quête) |
| Advanced Fluid Storage Housing | Boîtier ME Avancé stockage Fluides | AE2FC, NEI FR |
| Level Maintainer | Mainteneur Niveau ME | AE2FC, NEI FR |
| Fluid Auto Filler | Remplisseur ME auto Fluides | AE2FC, NEI FR |
| Certus Tank | Réservoir Quartz Certus | AE2FC, NEI FR |
| Fluid Digital Singularity Cell | Cellule ME Singularité Digitale stockage Fluides | AE2FC, NEI FR |
| Energy Card | Carte d'énergie | AE2FC, NEI FR |
| Network Tool, Memory Card, Priority Card, cartes (Redstone/Capacity/Crafting/Acceleration/Fuzzy/Inverter…), Inscriber, Molecular Assembler, Cell Workbench, ME IO Port, Spatial IO Port, Quartz Fiber, Cable Anchor | (inchangés) | AE2, anglais en jeu |
| AE Tier N Item/Fluid Storage (titres) | Stockage d'objets/de fluide AE, tier N |  |
| Short Guide - X (titres) | Petit guide - X |  |
| Beam Me Up, Scotty | Téléportez-moi, Scotty | référence Star Trek |
| Gotta Find Them All | Attrapez-les tous | référence Pokémon |

### Comment être (abeille)

| Anglais | Français | Remarque |
|---|---|---|
| How to Be(e) (questline) | Comment être (abeille) | nom d'onglet fixé par le brief |
| bee / princess / queen / drone | abeille / princesse / reine / faux bourdon | termes génériques ; noms NEI d'espèces (Forest Drone…) en anglais |
| larvae (Larvae) | larves (Larvae) | l'objet Forestry « Larvae » reste en anglais |
| hive / comb / silky comb | ruche / rayon / rayon soyeux | objets NEI (Silky Comb, Honey Comb) en anglais |
| frame (bee) | cadre | objets NEI en anglais : Untreated / Impregnated / Proven / Magic / Soul / Accelerated / Oblivion / Mutagenic Frame |
| pristine / ignoble (stock) | pristine / ignoble | gardés tels quels (lignée Pristine Stock / Ignoble Stock en jeu) |
| jubilant (state) | état jubilant |  |
| trait / gene / gene sample / template | trait / gène / échantillon de gène / modèle | objets Gendustry (Gene Sample, Blank Gene Sample, Genetic Template, Genetics Labware) en anglais |
| labware | labware | Genetics Labware (Gendustry) |
| breeding / crossbreeding | élevage / croisement |  |
| genetic decay | dégénérescence génétique |  |
| lifespan / fertility / territory / pollination / mutation rate | durée de vie / fertilité / territoire / pollinisation / taux de mutation |  |
| butterfly / caterpillar / sapling | papillon / chenille / pousse |  |
| apiarist / beekeeper (villager) | apiculteur / villageois apiculteur | objets « Apiarist's … » en anglais |
| Apiarist's suit / clothes | tenue / vêtements d'apiculteur | pièces : Apiarist's Hat/Shirt/Pants/Shoes |
| scoop | filet | « Scoop » GT reste Scoop (nom NEI) ; le Scoop Forestry s'affiche « Filet » |
| Bee House, Apiary, Alveary, Swarmer, Alveary Fan/Heater/Hygroregulator/Stabiliser/Sieve, Frame Housing, Hatchery, Mutator, Rain Shield, Alveary Lighting, Alveary Transmission, Electrical Stimulator, Habitat Locator, Beealyzer, Flutterlyzer | (inchangés) | Forestry / Extra Bees, anglais en jeu |
| Mutatron, Advanced Mutatron, Genetic Sampler/Imprinter/Transposer/Replicator, Industrial Apiary, Mutagen, Liquid DNA, Protein, Pollen Collection Kit, Production Upgrade, Genetic Stabilizer Upgrade | (inchangés) | Gendustry, anglais en jeu |
| Isolator, Sequencer, Polymeriser, Inoculator, Splicer, Genepool, Incubator, Acclimatiser, Lab Stand, Gene Database, Registry, Master Registry, Serum Vial/Array, Blank Sequence, DNA Sequence, Growth Medium, Enzyme, Fluorescent Dye, Raw DNA, Bacteria, Bacteria Vector, Polymerizing Bacteria | (inchangés) | Binnie Genetics, anglais en jeu (orthographe NEI « Polymeriser ») |
| Silk Wisp / Woven Silk / Silky Propolis / Royal Jelly / Aromatic Lump | (inchangés) | objets Forestry/Magic Bees |
| Bee Collector's Jar | (inchangé) | Magic Bees ; « collector's jar » du texte rendu par ce nom |
| meta (Oblivion bee meta) | méta | « la méta Oblivion » |

### Élevage d'abeilles

| Anglais | Français | Remarque |
|---|---|---|
| Be(e) Breeding (questline) | Élevage d'abeilles | nom d'onglet fixé par le brief |
| bee species names (Common, Cultivated, Tin, Lead, Platinum, Ur-Ghast, Batty, Arid...) | (inchangés, nom NEI) | noms d'espèces Forestry/ExtraBees/MagicBees/GT en anglais en jeu ; « une abeille Tungsten », « obtenez-les en croisant X et Y » |
| Copper / Iron / Diamond / Steel / Stainless Steel / Energetic Alloy / Pyrotheum (espèces GT) | Cuivre / Fer / Diamant / Acier / Acier inoxydable / Alliage énergétique / Pyrothéum | espèces d'abeilles traduites en jeu (GregTech lang) ; titre « Pyrotheum » corrigé en « Pyrothéum » |
| drone / princess / queen / larvae | faux-bourdon / princesse / reine / larve | générique ; objets NEI « Common Princess » etc. restent en anglais |
| comb(s) (générique) | rayon(s) | « rayons de Cuivre » ; objets nommés (Honey Comb, Dripping Combs, Wheaten Comb, Simmering Combs...) en anglais |
| hive (sauvage) / bee housing | ruche sauvage / logement (pour abeilles) | Apiary, Bee House, Alveary, Industrial Apiary, Deep Hive restent en anglais |
| breed / cross-breed / breeding | élever / croiser / élevage | « Breed them from X and Y » = « Obtenez-les en croisant X et Y » |
| mundane bee | abeille ordinaire |  |
| pure / active / inactive trait | pure / trait actif / inactif |  |
| Ignoble / Pristine princess | princesse Ignoble / Pristine | qualificatifs affichés en anglais en jeu |
| fertility / lifespan / territory / pollination / production speed | fertilité / durée de vie / territoire / pollinisation / vitesse de production | valeurs d'allèles (Fast, Fastest, Blinding, Large, Hellish, Arid, Icy...) gardées en anglais |
| jubilant | jubilante | état de la reine |
| frame | cadre | objets nommés (Proven Frame, Oblivion Frame, Soul Frame) en anglais |
| Apiarist suit | combinaison d'apiculteur | aussi « Apiarist Suit » quand l'original met la majuscule |
| Breeder's / Beekeeper's / Trader's / Thaumaturge's / Astronomer's Notes | Notes de l'éleveur / de l'apiculteur / du marchand / du thaumaturge / de l'astronome |  |
| Royal Jelly, Honeydew, Ambrosia, Scented Paneling, Aromatic Lump, Enchanting Drop, Pollen Cluster, Silk Wisp, Soulful Wax, Amnesiac Wax, Refractory Wax, Mulch | (inchangés) | objets Forestry/Magic Bees, anglais en jeu |
| Crystal Cluster (Air/Earth/Fire/Water/Order/Entropy), Salis Mundus | (inchangés) | Thaumcraft, anglais en jeu |
| X infused dust | poudre infusée d'Air / de Terre / de Feu / d'Eau / d'Ordre / d'Entropie | générique |
| node (Thaumcraft) | nœud |  |
| Acclimatiser, Inoculator, Splicer, Polymerizer, Mutatron, Advanced Mutatron, Escritoire, Nature's Compass, Habitat Locator, Golden Lasso, Apimancer's Drainer | (inchangés) | machines/objets en anglais en jeu |
| Climate Control Module | unités de contrôle climatique (Climate Control Module) | nom NEI rappelé entre parenthèses |
| Gassy Bees / Space Bees / Fruity bees | Abeilles gazeuses / Abeilles de l'espace / Abeilles Fruity | titres de quête |
| Breed some X bees | Élevez des abeilles X | titres de quête |
| beekind | abeillité | jeu de mots « un bond de géant pour l'abeillité » |

### HEE, Thaumaturgie adepte

| Anglais | Français | Remarque |
|---|---|---|
| Objets/blocs/mobs Hardcore Ender Expansion (End Powder, Endium Ore/Ingot, Igneous Rock, Instability Orb, Stardust, Dragon Essence, Essence Altar, Enhanced Brewing Stand, Biome Compass, Ender Goo, Charm Pouch, Charms, Runes (Rune of Power…), Curse of X, Living Matter, Ectoplasm, Fire Fiend, Louse, Haunted Miner…) | (inchangés) | fichier lang HEE entièrement en anglais |
| Biome Islands / Infested / Enchanted / Fiery Island | îles de biome / île infestée / île enchantée / île ardente | concepts ; variantes (Deep, Ravaged, Homeland, Laboratory, Scorching, Mine) gardées en anglais |
| infestation (HEE) | infestation |  |
| Dungeon Tower (HEE) | tour de donjon |  |
| pedestal (autel HEE) | piédestal |  |
| enhancement (End Powder) | amélioration |  |
| vanilla : Brewing Stand / Awkward Potion / splash potion / Beacon / Iron Fence / Silverfish / Iron Golem | Alambic / Potion étrange / potion jetable / Balise / Barreaux de fer / Poisson d'argent / Golem de fer | noms vanilla FR |
| effets vanilla : Slowness / Weakness / Mining Fatigue / Blindness / Nausea / Haste / Night Vision / Water Breathing / Fire Resistance / Regeneration | Lenteur / Faiblesse / Fatigue / Cécité / Nausée / Célérité / Vision nocturne / Respiration aquatique / Résistance au feu / Régénération |  |
| Silk Touch / Fortune | Toucher de soie / Fortune | enchantements vanilla |
| wand / staff / scepter / staffter | baguette / bâton / sceptre / « bâtceptre » | Thaumcraft, texte courant |
| wand cap / wand core (rod) / staff core | capuchon / noyau de baguette (tige) / noyau de bâton | objets eux-mêmes en anglais (Gold Cap, Silverwood Rod, Bone Staff Core…) |
| wand augmentation (Thaumic Machina) | augmentation de baguette | Charge Buffer, Vis Channel inchangés |
| node / stabilized node / energized node | nœud / nœud stabilisé / nœud énergisé |  |
| vis / centi-vis / essentia / flux | vis / centi-vis / essentia (fém.) / flux | screw = vis aussi (« vis en Oriharukon ») ; préciser « vis (la magie) » si ambigu |
| warp (permanent / normal / temporary) | warp (permanent / normal / temporaire) | masc. |
| jar | bocal |  |
| focus (Thaumcraft) | focalisateur | objets « Wand Focus: Shock », améliorations Potency / Chain Lightning / Earth Shock en anglais |
| bath salts | sels de bain | objet : Purifying Bath Salts |
| Litmus Paper | Arcane Litmus Paper | nom en jeu |
| Objets Thaumcraft et addons (Thaumonomicon, Primal Charm, Node Stabilizer, Essentia Locus/Mirror/Aggregator, Crystalline Eye, Shovel of the Purifier, Sanitizing Soap, Silverwood Smoking Pipe, Relaxing Tobacco, Soul Brazier, Node Manipulator, Golemancer's Bell, Traveling Trunk, Pure Tear, Arcane Spa, Eldritch Portal, Outer Lands, Crimson Knight/Cleric, Warp Ward, Purifying Fluid, Dynamism Tablet) | (inchangés) | anglais en jeu (sauf Thaumomètre, Établi arcanique) |
| Ender Chest / Ender Tank / Ender Pouch (EnderStorage) | (inchangés) | titres de quête : « Une boîte magique », « Un réservoir magique » |
| Division Sigil / Pseudo-Inversion Sigil | (inchangés) | Extra Utilities ; « sceau » en texte courant |
| Energetic Alloy (vis de baguette) | Energetic Alloy | EnderIO, anglais (le matériau GT affiche « Alliage énergétique ») |
| She Let Go (titre) | Libérée, délivrée | clin d'œil à La Reine des neiges |

### Thaumaturgie novice

| Anglais | Français | Remarque |
|---|---|---|
| Novice Thaumaturgy | Thaumaturgie novice | nom de chapitre (table du brief) |
| wand | baguette | nom commun ; les objets nommés restent en anglais (Gold Banded Greatwood Wand, Iron Capped Greatwood Wand) |
| scepter | sceptre | nom commun |
| wand caps / wand core (rod) | embouts / cœur de baguette | déjà au glossaire Adept ; « baguette en Greatwood à embouts en or » |
| node / aura node | nœud / nœud d'aura | Thaumcraft ; « nœuds pâles » (Pale), « nœuds Eerie », « nœuds corrompus » (Tainted) |
| vis | vis (féminin, invariable) | « drainer de la vis », « 50 vis », « réduction de vis » |
| vis discount | réduction de vis |  |
| primal / compound aspects | aspects primaires / aspects composés | noms d'aspects en latin (Ordo, Aqua, Auram, Praecantatio…) |
| infused shards / infused stones | éclats infusés / pierres infusées | objets précis en anglais (Air Shard, Balanced Shard, Air Infused Stone) |
| crystal cluster | amas de cristaux | objets précis en anglais (Air Crystal Cluster) |
| infusion / infusion altar | infusion / autel d'infusion |  |
| Arcane Workbench / arcane table | Établi arcanique | traduit dans le lang FR de Thaumcraft |
| Thaumometer | Thaumomètre | traduit dans le lang FR de Thaumcraft |
| Advanced Alchemical Furnace | Four alchimique avancé | traduit en jeu ; l'Alchemical Furnace simple reste en anglais |
| Crucible, Alchemical Furnace, Arcane Alembic, Warded Jar, Essentia Buffer, Research Table, Scribing Tools, Thaumonomicon, Goggles of Revealing, Boots of the Traveller, Primal Charm, Enchanted Fabric, Paving Stone of Warding, Ethereal Bloom, Shimmerleaf, Vishroom, Zombie Brain, Ethereal Essence, Quicksilver, Knowledge Fragment | (inchangés) | Thaumcraft, anglais en jeu |
| Thaumcraft research names (Research, Research Expertise, Deconstruction table, Container Scanning, Substitution, Basic Information, Maleficia, Thaumic Nature) | (inchangés) | anglais en jeu |
| Warp / Taint / Flux / Flux Flu / Flux Phage / Tainted Lands / Fibrous Taint / Thaumic Slime | (inchangés) | termes Thaumcraft, anglais en jeu ; « Flux Flue » du texte source = Flux Flu en jeu |
| Potion of Blissful Oblivion | (inchangé) | Warp Theory |
| Automagy (Greedy Chest, Corporeal Attractor, Soul Mold, Crystalline Brain/Eye, Avarice Pearl, Shattered Avarice Pearl, Remote Comparator, Tally Box, Runic Whitelist, Redcrystal, Advanced Redcrystal, Thirsty Tank) | (inchangés) | anglais en jeu |
| Thaumic Bases plantes (Redlon, Metalleat, Lucrite, Lazullia, Rainbow Cacti, Briar, Briar Seed Bag, Rosehip Syrup, Sweed, Glieonia, Aurelia, Rosa Mysteria) | (inchangés) | anglais en jeu |
| Spinning Wheel / Arcane Abacus | Spinning Wheel / Arcane Abacus | Witching Gadgets, anglais en jeu (« rouet » en texte courant) |
| Twilight Forest items (Naga Scale, Raven's Feather, Torchberries, Liveroot, Magic Map, Magic Map Focus, Ironwood, Knightmetal, Timewood Clock, Tree of Time, Canopy Tree) | (inchangés) | anglais en jeu ; Steeleaf = Feuilleacier (traduit en jeu) |
| Lignite | Charbon de Lignite | matériau GT |
| Extra Utilities (Division Sigil, Cursed Earth, Golden Lasso) / TiC (Silky Jewel, Red Heart Canister) | (inchangés) | anglais en jeu |
| silk touch | Toucher de soie | enchantement vanilla FR |
| brewing stand / enchantment table / comparator | alambic / table d'enchantement / comparateur | blocs vanilla FR |
| Pech | Pech | créature Thaumcraft ; titre « Un marchand pech-ulier » (jeu de mots) |

### Focalisateurs, Flower Power, Prix fort

| Anglais | Français | Remarque |
|---|---|---|
| wand focus / foci (générique) | focalisateur(s) (de baguette) | masculin ; aligné sur le nom de l'onglet « Focalisateurs de baguette et EMT » ; les objets « Wand Focus: X » restent en anglais (NEI) |
| Focal Manipulator / améliorations de focus (Frugal, Potency, Enlarge, Treasure, Architect…) | (inchangés) | anglais en jeu (Thaumcraft) ; « améliorations » en texte courant ; niveau = niveau, even/odd levels = niveaux pairs/impairs |
| caster (sort) | lanceur |  |
| sticky warp / temporary warp | warp persistant / warp temporaire | Warp non traduit |
| taint / tainted | taint / corrompu | « taint » gardé comme nom ; adjectif « corrompu » (bulles corrompues) |
| Flux Flu, Pech Mage, Warded Glass, Nitor, Arcane Bore, Hoe of Growth, Crystallized Essence, Native Clusters | (inchangés) | Thaumcraft, anglais en jeu |
| Mjolnir, Guardian Snowman, Shield Block, Electric Scribing Tools | (inchangés) | EMT, anglais en jeu |
| to ward / warded block | protéger / bloc protégé | Warding |
| Botania : Mana Pool, Mana Spreader, Petal Apothecary, Livingrock, Wand of the Forest, Runic Altar, Lexica Botania, Spark, Managlass, Alfglass, Guardian of Gaia, Shard of Laputa, Ring of Magnetization, Redstone Root, Mana Powder, noms des fleurs (Daybloom, Endoflame, Hydroangeas…) | (inchangés) | Botania, anglais en jeu (« Guardian of Gaia » = nom d'entité en jeu) |
| mana pool (générique) | bassin de mana | Mana Pool quand on désigne l'objet |
| generating / functional flower | fleur génératrice / fleur fonctionnelle | « Fleur génératrice » = libellé Botania FR en jeu |
| Manasteel / Terrasteel / Mana Diamond / Gaia Spirit (contexte Botania) | (inchangés) | objets Botania anglais ; DOUTE : GT a les matériaux Manacier / Terracier / Diamant de Mana / Esprit de Gaïa |
| Mana Fountain, Fountain of Alchemy, Fountain of Conjuration, Synthetic Elven Gateway, Elven Gateway | (inchangés) | multiblocs, féminin (« la Mana Fountain ») |
| Blood Magic : Blood Altar, Blood Rune, Rune of …, Ritual Stone, Ritual Diviner, Sacrificial Knife, Dagger of Sacrifice, Blood Letter's Pack, Incense Crucible, Crystal Belljar, Arcane Plinth, Soul Forge, noms de rituels et de sigils | (inchangés) | anglais en jeu |
| altar / slate / sigil / orb / chalk / ritual (générique) | autel / ardoise / sceau / orbe (masc.) / craie / rituel | titres « Sceaux de tier 2 », « Ardoises de tier 1 » |
| soul network / LP | réseau d'âme / LP |  |
| incense / incense value | encens / valeur d'encens | noms d'encens (Wood Ash, Byrrus, Livens, Viridis, Purpura) inchangés |
| I/O buffer (autel) | réserve d'E/S |  |
| bound tools / bound armor | outils liés / Bound Armor |  |
| blood mage / battlemage | mage de sang / mage de guerre |  |
| Dusk (runes/craie) | du crépuscule (Dusk) |  |
| vanilla : Silk Touch / Fortune / Projectile Protection / Slowness / Weakness / Nausea | Toucher de soie / Fortune / Protection contre les projectiles / Lenteur / Faiblesse / Nausée | noms FR vanilla |

### Regardez vers les confins

| Anglais | Français | Remarque |
|---|---|---|
| Witchery (objets/blocs : Witches Oven, Altar, Kettle, Distillery, Spinning Wheel, Witch's Cauldron, Clay Jar, Fume Funnel, Mutandis, Attuned Stone, Poppet, Dream Weaver, Arthana, Taglock Kit, Seer Stone…) | (inchangés) | fichier lang fr de Witchery entièrement en anglais |
| Witchery rites (Rite of Charging, Rite of Infusion, Rite of Summoning, Rite of Binding…) | (inchangés) | noms des livres en jeu, en anglais |
| Witchery books (Witches' Brews, Witchcraft: Distilling, Witchcraft: Circle Magic, Book of Biomes) | (inchangés) | titres en jeu |
| spirit world / Spirit World | monde des esprits | concept |
| dream world | monde des rêves | concept |
| nightmare (rêve) / Nightmare (mob) | cauchemar / Nightmare | le mob garde son nom anglais |
| circle magic | magie des cercles | concept |
| altar power | énergie d'autel |  |
| coven / Coven Witches | coven / Coven Witches |  |
| familiar | familier |  |
| taglock | taglock | terme Witchery non traduit |
| witchwear | tenue de sorcière |  |
| Granny Weatherwax | Mémé Ciredutemps | nom français officiel (Annales du Disque-monde) |
| Rumplestiltskin | Tracassin | nom français du conte |
| Coins tab | onglet Coins | aucun chapitre de ce nom dans la liste ; laissé tel quel |
| BM tab | onglet Payer le prix fort | chapitre Blood Magic |
| Looting | Butin | enchantement vanilla |

### Tuez-les tous

| Anglais | Français | Remarque |
|---|---|---|
| Kill All the Things | Tuez-les tous | nom du chapitre (table du brief) |
| Time to Kill (X) | Il est temps de tuer (X) | série de titres ; X = nom du monstre en jeu |
| Kill X (titre) | Tuer X | ex. « Tuer Baba Yaga » |
| X: Evolved (Skeleton/Creeper/Blaze…) | X : version évoluée | série de titres Galacticraft ; « Killing: Evolved » = « Massacre : version évoluée » |
| monstres vanilla | Creeper, Zombie, Squelette, Squelette Wither, Araignée, Enderman, Blaze, Ghast, Wither, Sorcière, Cochon zombie, Chauve-souris, Cube de magma, Slime, Poisson d'argent, Mouton, Vache, Cochon, Poulet, Poulpe | noms FR de Minecraft |
| monstres de mods | anglais | TF (Naga, Lich, Minoshroom, Knight Phantom, Ur-ghast, Snow Queen, Alpha Yeti, Kobold, Redcap, Fire/Slime/Pinch Beetle, Swarm Spider, Twilight Wraith…), Witchery (Baba Yaga, Horned Huntsman, Shade of Leonard, Lord of Torment, Demon, Hellhound, Hobgoblin), HEE (Ender Eye, Ender Guardian, Fire Golem, Haunted Miner, Louse, Scorching Lens), Et Futurum (Husk, Stray, Fox, Rabbit, Shulker), GC (Evolved Skeleton/Creeper), Natura (Imp, Nitro Creeper), Special Mobs (Lava Monster, Witch Spider), TiC (King Slime), Thaumcraft (Crimson Knight, Wisp, Thaumic Slime), DE (Chaos Guardian) |
| Dire Wolf (Ender Zoo) | Loup Garou | nom FR en jeu (entity.enderzoo.DireWolf) |
| Ender Dragon | Ender Dragon | nom en jeu (HEE/Et Futurum FR) |
| Infernal (statut Infernal Mobs) | Infernal | non traduit |
| Hollow Hills / Dark Tower / Goblin Knight Stronghold | (inchangés) | lieux TF ; Labyrinths = labyrinthes, Hedge Mazes = labyrinthes de haies, Leaf Dungeons = donjons de feuilles |
| Wild Hunt / Horned God | Chasse sauvage / Dieu cornu | Witchery |
| Trigger: X | Déclencheur : X | quêtes techniques hors chapitre |
| Trigger: X Skip | Déclencheur : saut X | matériaux au nom FR en jeu |
| No Description | Aucune description |  |
| Naqline | ligne du Naquadah |  |
| Spawn Egg | œuf d'apparition |  |
| Phantom Busters (Ghostbusters) | S.O.S. Phantoms | jeu de mots sur S.O.S. Fantômes |
| Let Her Go (Frozen) | Libérée, délivrée | titre adapté |
| Planètes : Ceres / Europa / Ganymede / Enceladus / Proteus | Cérès / Europe / Ganymède / Encelade / Protée |  |

### Quêtes partagées 1

| Anglais | Français | Remarque |
|---|---|---|
| Iron Chests (Copper/Iron/Gold/Diamond Chest) | coffre en cuivre / en fer / en or / en diamant | noms FR en jeu (Iron Chests) ; upgrade item = objet d'amélioration |
| Filing Cabinet (Extra Utilities) | Filing Cabinet | anglais en jeu ; « cabinet » de la quête = Filing Cabinet |
| drawer (Storage Drawers) | tiroir | texte courant ; noms d'objets (Oak Drawer…) en anglais |
| barrel (générique) | tonneau | Steel Barrel / Copper Barrel restent en anglais (Et Futurum) |
| main quest / optional quest | quête principale / quête optionnelle |  |
| Battery Alloy | Alliage pour Batterie | matériau GT (S:Material.batteryalloy) |
| Oil / Heavy Oil / Light Fuel | Pétrole / Pétrole Lourd / Carburant léger | matériaux GT |
| oil spout | geyser de pétrole |  |
| Heat Vent / Heat Exchanger / Reactor Chamber / Sensor Kit / Display Panel | (inchangés) | objets IC2 / Nuclear Control, « une Heat Vent » (féminin) |
| Hu/t (heat units per tick) | unités de chaleur par tick (Hu/t) |  |
| crossbow / crossbow limb / crossbow body / bolt | arbalète / branche d'arbalète / corps d'arbalète / carreau | Tinkers ; Fiery Bowstring reste en anglais |
| throwing knife / javelin | couteau de lancer / javelot | texte courant ; titre « Bronze Javelin » gardé (nom d'objet) |
| bauble slot | emplacement de bauble |  |
| focus / foci (Thaumcraft) | focalisateur(s) | modificateurs Frugal / Potency / Enlarge inchangés |
| Celestial Gateway / Celestial Pearl | (inchangés) | noms d'objets |
| Kinetic Power HV | Énergie cinétique HV | série « Énergie éolienne / hydraulique cinétique » |
| Windmeter / Windmill / Gearbox Rotor | (inchangés) | noms d'objets |
| ore chunk | chunk à minerai |  |
| Bookmarks (NEI) | favoris |  |
| Aluminium Iron Plate | Aluminium Iron Plate | objet, pas de clé GT FR trouvée |

### Quêtes partagées 2

| Anglais | Français | Remarque |
|---|---|---|
| Moron's Manual / Moron's Guide for X | X pour les nuls | série de titres (« Massacrer des monstres pour les nuls », « L'EBF efficace pour les nuls », « Élever de meilleures abeilles pour les nuls ») |
| Mallard Rust Smelly (pun Alloy Blast Smelter) | Allô ? Blast Smelter ? | jeu de mots adapté |
| storage drawers / drawer / barrel | tiroirs de stockage / tiroir / tonneau | objets NEI (Drawer Key, Drawer Controller, Controller Slave, Trim, Void Upgrade) en anglais |
| breeding stock (bees) | cheptel d'élevage | princesses/faux bourdons de référence |
| master template bee | abeille modèle |  |
| pristine / ignoble (princess) | immaculée / ignoble |  |
| jubilant (bee state) | « jubilant » | état Forestry, gardé entre guillemets |
| Cave Dwelling / Nocturnal / Rain Tolerant / High Fertility | cavernicole / nocturne / tolérance à la pluie / fertilité élevée | traits d'abeille ; espèces (Rocky, Water, Wintry, Salt) en anglais |
| Witchery plants (Mandrake, Belladonna, Snowbell, Water Artichoke, Wolfsbane, Garlic Garland, Icy Needle) | (inchangés) | anglais en jeu ; garlic générique = ail |
| Brew / Rite of Shifting Seasons, Ritual of Gaia's Transformation, Cry of the Eternal Soul, Arcane Terrestrial Reformer | (inchangés) | anglais en jeu |
| Launch Controller, Fuel Loader, Cargo Loader/Unloader, Rocket Launch Pad, Cargo Rocket, Oxygen Gear, Thermal Padding, SpaceSuit | (inchangés) | Galacticraft, anglais en jeu |
| Arc Lamp, Plated Reinforced Stone, Warded Glass, Lunch Box, Crafting Station, Rapier | (inchangés) | objets, anglais en jeu |
| ghost circuit / programmed circuit | circuit fantôme / circuit programmé |  |
| keybind | raccourci clavier |  |
| ore milling | broyage fin des minerais (ore milling) | IsaMill / Flotation Cell |
| nanite (Nano Forge) | nanite (féminin) | « nanite de Neutronium » ; objets « Carbon Nanites » en anglais |
| Heat Resistant / Heat Proof Casings | (inchangés) | casings ICO |

### Quêtes partagées 3

| Anglais | Français | Remarque |
|---|---|---|
| waterline (purification de l'eau) | chaîne de l'eau | « Comme d'habitude avec la chaîne de l'eau » |
| Pebble Bed reactor / pebbles (HTGR) | réacteur à lit de boulets / boulets | High Temperature Gas-cooled Reactor reste en anglais |
| trace size (PCB Factory) | taille des pistes (trace size) |  |
| circuit board (générique) | circuit imprimé | objets nommés (Wetware/Bioware boards) en anglais |
| nanite(s) | nanite(s) (féminin) | objets : Silver/Gold/Carbon/Transcendent/Magmatter Nanite(s) restent en anglais |
| Super Coolant / Supercoolant | Super Coolant / Supercoolant | gardé selon le glossaire existant (GT FR : Super Réfrigérant) |
| Exo-Foundry bonus (Optimum Production, Superstable Core, Harmonic Efficiency, Realized Potential) | (inchangés) | noms affichés en jeu, entre « » |
| Matter Manipulator modes (Geometry, Cable, Exchange, Copy/Paste, Move) | Géométrie / Câble / Échange / Copier / Coller / Déplacer (nom anglais entre parenthèses) | options Advanced Options / Link to External Hubs / Auto-P2P Interfaces / Auto-Proxy CRIBs en anglais (UI) |
| LHC UI (Collision Energy, Rest Mass, Beam Energy, Number of Cycles, Amount, Accelerator/Collider) | (inchangés) | libellés affichés en jeu |
| powerfail | panne de courant |  |
| Pick Block (touche) | Choisir le bloc | nom FR de la touche vanilla |
| shulker shell | carapace de shulker | Shulker Box reste en anglais |
| wallsharing | partage de murs / partager leurs murs | cf. « wallshare » existant |
| NEI search terms (extended+, space mode, recipe search field) | extended+ / mode espace / champ de recherche de recettes |  |
| backtick | accent grave |  |

---

## 9. Arbitrages

| Terme | Décision |
|---|---|
| Superheated Steam | « Superheated Steam » quand on désigne le fluide précis (nom NEI) ; « vapeur surchauffée » acceptée dans la prose générique. |
| fuel efficiency | « rendement du carburant ». |
| Perfect Overclock | « overclock parfait ». |
| Balises `[quest]…[/quest]` | Contiennent le titre de la quête ciblée : on y met le titre tel qu'affiché en jeu (français s'il est traduit). Si la quête ciblée n'existe pas dans le fichier, on garde le texte anglais d'origine. |
| Noms de chapitres | Voir la table des chapitres traduits (Objectifs multiblocs, Course à l'espace, etc.) ; toujours les citer sous ce nom. |
