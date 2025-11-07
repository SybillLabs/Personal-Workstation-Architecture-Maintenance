# 💻 Personal Workstation : Architecture et Maintenance 🛠️

## 📄 Contexte
Comme beaucoup de techs, mon ordinateur est **mon outil principal — et un peu mon bébé** 🖥️  
Je l’entretiens, je l’optimise et je le fais évoluer selon mes besoins.

J’utilise ma machine pour :
- 🎮 **Gaming** — *The Division 2, Elite Dangerous, Cyberpunk 2077, FFXIV…*
- 📺 **Divertissement** — *Manga, séries, films…*
- 🧾 **Bureautique**
- 🧱 **Virtualisation** — *VMware, tests d’environnements isolés*
- 🌐 **Infrastructure Système & Réseau**
- 🕵️ **Pentesting & sécurité informatique**

J’ai créé ce dépôt pour garder un suivi complet de ma workstation, notamment sur :
- 🧩 Son **architecture matérielle**
- 🔩 Son **historique de montage et d’upgrades**
- 📜 Ses **scripts de maintenance**

## 🧩 Architecture du système

| Composant | Modèle / Référence | Rôle / Commentaire |
|------------|--------------------|--------------------|
| 💽 **OS** | 🪟 Windows 11 Famille / 🐧 Kubuntu | Windows pour le gaming, divertissement et bureautique — Kubuntu pour la virtualisation, l’infra et la sécu |
| 🧠 **CPU** | AMD Ryzen 7 5800X (3.8 GHz / 4.7 GHz) | Excellent ratio performance/efficacité — idéal pour multitâche et virtualisation |
| 🧬 **Carte mère** | ASUS ROG CROSSHAIR VIII HERO WIFI | Haut de gamme stable, bon support overclocking et monitoring |
| 🧮 **RAM** | G.Skill Ripjaws V Black — 4 × 8 Go (32 Go) DDR4 3200 MHz CL16 | Dual Channel complet — équilibre parfait entre perf et compatibilité |
| 🎮 **GPU** | ASUS TUF GeForce RTX 3070 O8G GAMING | Excellent compromis gaming / CUDA / virtualisation GPU |
| 💾 **Stockage** | KINGSTON SNV2S2000G (2 To NVMe) — Jeux<br>Samsung 860 EVO (250 Go SSD) — OS Kubuntu<br>KINGSTON A400 (250 Go SSD) — OS Windows<br>TOSHIBA MK1059GSM (1 To HDD) — Données Windows<br>WDC WD10EZEX (1 To HDD) — Données Kubuntu | Architecture multi-disques : séparation des OS et des espaces de travail |
| 🔌 **Alimentation** | ASUS ROG STRIX 850 W Gold Aura Edition | Excellente marge de puissance et certification 80+ Gold |
| 🧊 **Refroidissement** | ASUS ROG Strix LC II 360 ARGB AM5<br>2 × Corsair iCUE Link LX120 RGB (Pack Triple, AirGuide, Hub inclus) | Refroidissement liquide performant, flux d’air optimisé et esthétique RGB |
| 🖥️ **Boîtier** | Corsair 5000D Airflow TG Black (ATX) | Flux d’air exemplaire, gestion des câbles facile et grand espace intérieur |


### 💻 Ordinateur
![ordinateur](/Ressources/ordinateur.png)

### 🚀 Améliorations possibles
- Augmenter la RAM à 64 Go pour une meilleure gestion des **VM** pour mes projets
- Passer la RAM de 3200 MHz à 3600MHz pour une meilleure latence sur mes jeux vidéo

## 🔩 Historique de montage

| Date | Composant | Action | Détails / Motivation |
|------|------------|---------|----------------------|
| 25/07/2019 | 🧮 RAM | Montage initial | G.Skill Ripjaws V Black – 2 × 8 Go (16 Go) DDR4 3200 MHz CL16 |
| 23/06/2020 | 🧮 RAM | Upgrade | Passage à 32 Go pour plus de confort et de performance |
| 04/02/2021 | 🎮 GPU | Upgrade | ASUS TUF GeForce RTX 3070 O8G GAMING — meilleur suivi et qualité pour le gaming |
| 26/05/2023 | 🔌 Alimentation | Upgrade | ASUS ROG STRIX 850W Gold Aura Edition — pour harmoniser le setup full ASUS |
| 26/05/2023 | 🧬 Carte mère | Upgrade | ASUS ROG CROSSHAIR VIII HERO WIFI — WiFi intégré et plus de ports USB |
| 26/05/2023 | 🧊 Refroidissement | Upgrade | ASUS ROG Strix LC II 360 ARGB AM5 — meilleur refroidissement CPU et gain de place |
| 04/07/2025 | 🧠 CPU | Upgrade | AMD Ryzen 7 5800X — plus de cœurs/threads pour la virtualisation |
| 27/06/2025 | 🖥️ Boîtier | Upgrade | Corsair 5000D Airflow TG Black (ATX) — meilleur airflow et gestion de la pression positive |
| 09/07/2025 | 🧊 Refroidissement | Upgrade | 2 × Corsair iCUE Link LX120 RGB (Pack Triple) — atteindre une pression positive et airflow optimal |

> Le suivi des disques durs n’est pas détaillé ici, certains étant anciens ou issus de disques externes reconvertis en internes. Leur traçabilité complète serait donc peu pertinente.

### 💨 Gestion du flux d’air
J’ai opté pour une configuration en **pression positive**, c’est-à-dire avec **plus d’air entrant que sortant**.  
Ce choix permet :
- De **réduire significativement l’accumulation de poussière** à l’intérieur du boîtier (l’air s’échappe par les interstices, empêchant les impuretés d’entrer).  
- D’**améliorer la circulation générale de l’air** autour des composants sensibles (GPU, VRM, RAM).  
- De **mieux contrôler le flux d’air**, en synchronisant les ventilateurs d’admission et d’extraction.

J’ai écarté la **pression négative** (trop sujette à l’aspiration de poussière non filtrée) et la **pression neutre** (moins efficace pour canaliser le flux d’air).  
Grâce au **Corsair 5000D Airflow** et aux **ventilateurs iCUE Link LX120**, cette configuration offre un **équilibre idéal entre refroidissement, silence et propreté interne**.


## 🔧 Maintenance
### 🧹 Nettoyage de l’ordinateur
J’effectue un nettoyage complet de l’intérieur de la machine **deux fois par an**, afin de maintenir un bon flux d’air et de prévenir toute accumulation de poussière.  
L’extérieur, notamment les grilles de ventilation et filtres, est **entretenu mensuellement**.

Pour le nettoyage :
- 🧽 **Extérieur** : essuyage au chiffon doux pour retirer la poussière de surface.  
- 🌬️ **Intérieur** : utilisation d’un [souffleur électrique](https://www.amazon.fr/dp/B01G1Z0RF0?ref=ppx_yo2ov_dt_b_fed_asin_title) équipé de plusieurs embouts, permettant un dépoussiérage précis et sécurisé sans contact direct avec les composants.

### ⚙️ Scripts de maintenance
#### 🪟 Windows 11 Famille
🚧 **En cours d'écriture**

#### 🐧 Kubuntu
🚧 **En cours d'écriture**

---

## ⚠️ Disclaimer

Ce dépôt documente **ma workstation personnelle**, conçue selon **mes besoins, préférences et contraintes matérielles**.  
Les configurations, choix de composants et scripts présents ici **ne constituent pas des recommandations universelles**.  

> L’auteur ne saurait être tenu responsable d’éventuels dommages matériels, pertes de données ou incompatibilités  
> résultant de la reproduction partielle ou totale de cette configuration sur un autre système.
