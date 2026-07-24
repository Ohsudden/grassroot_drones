# Scraping Vocabulary — ISW Daily War Briefs
**Study:** *The Role of Grassroots Innovation in Ukraine's Development of Unpiloted Systems*

> [!NOTE]
> These terms are designed for NLP frequency analysis of the Institute for the Study of War (ISW) daily briefs. Include both singular and plural forms, and consider case-insensitive matching. Terms are grouped thematically to support pattern analysis across categories.

---

## 1. Core Unpiloted Systems Terminology

These are the primary terms the NLP should track for frequency and pattern analysis.

| Term | Variants / Notes |
|------|-----------------|
| drone | drones |
| UAV | UAVs, unmanned aerial vehicle(s) |
| UAS | unmanned aerial system(s) |
| USV | USVs, unmanned surface vessel(s), uncrewed surface vessel(s) |
| UGV | UGVs, unmanned ground vehicle(s) |
| UUV | UUVs, unmanned underwater vehicle(s) |
| FPV | FPV drone(s), first-person view |
| unpiloted | unpiloted system(s), unpiloted vehicle(s) |
| unmanned | unmanned system(s), unmanned vehicle(s), unmanned platform(s) |
| uncrewed | uncrewed system(s), uncrewed vehicle(s) |
| remotely piloted | remotely piloted aircraft, RPA |
| loitering munition | loitering munitions |
| kamikaze drone | kamikaze drones, suicide drone(s) |
| one-way attack drone | one-way attack drones |

---

## 2. Specific Systems & Models

### Ukrainian Systems
| Term | Notes |
|------|-------|
| Bayraktar | TB2, Bayraktar TB2 |
| R18 | Aerorozvidka's octocopter |
| PD-1 | Ukrainian-made reconnaissance UAV |
| Furia | Ukrainian tactical UAV |
| Leleka | Leleka-100 |
| Punisher | Ukrainian strike drone |
| Shark | reconnaissance UAV |
| Magura | Magura V5, Ukrainian USV |
| Sea Baby | Ukrainian USV |
| Baba Yaga | large multirotor drone nickname |

### Foreign-Supplied Systems (to Ukraine)
| Term | Notes |
|------|-------|
| Switchblade | Switchblade 300, Switchblade 600 |
| Phoenix Ghost | US-supplied loitering munition |
| ScanEagle | US reconnaissance UAV |
| Puma | RQ-20 Puma |
| JUMP 20 | |
| Vector | |
| Warmate | Polish loitering munition |

### Russian / Iranian Systems (adversary context)
| Term | Notes |
|------|-------|
| Shahed | Shahed-131, Shahed-136, Iranian-made |
| Geran | Geran-1, Geran-2 (Russian designation for Shahed) |
| Lancet | Lancet-3, Russian loitering munition |
| Orlan | Orlan-10, Russian reconnaissance UAV |
| Zala | Russian reconnaissance UAV |
| Supercam | Russian UAV |
| Mohajer | Iranian-made UAV |

---

## 3. Drone Operations & Capabilities

| Term | Variants |
|------|----------|
| reconnaissance | aerial reconnaissance, drone reconnaissance |
| surveillance | drone surveillance |
| ISR | intelligence, surveillance, and reconnaissance |
| precision strike | precision strikes |
| aerial strike | aerial strikes |
| drone strike | drone strikes |
| drone attack | drone attacks |
| artillery correction | artillery spotting, fire correction |
| battle damage assessment | BDA |
| target acquisition | targeting |
| deep strike | long-range strike |
| maritime drone | naval drone |

---

## 4. Counter-Drone & Electronic Warfare

| Term | Variants |
|------|----------|
| counter-UAS | counter-drone, C-UAS |
| electronic warfare | EW |
| jamming | GPS jamming, signal jamming |
| spoofing | GPS spoofing |
| electronic countermeasure | ECM, electronic countermeasures |
| air defense | air defence |
| anti-drone | anti-drone system(s), anti-drone warfare |
| interception | intercepted, intercept |

---

## 5. Grassroots Innovation & Civil Society

These terms capture the grassroots/innovation dimension central to the study.

| Term | Variants |
|------|----------|
| volunteer | volunteers, volunteer unit(s), volunteer battalion(s) |
| crowdfunding | crowd-funding, crowdsourced |
| grassroots | grassroots innovation, grassroots effort(s) |
| civil society | civilian volunteers |
| donation | donations, fundraising |
| 3D printing | 3D-printed, additive manufacturing |
| improvised | improvised drone(s), field modification(s) |
| modification | modified, adapt, adaptation |
| innovation | innovate, innovative |
| startup | start-up, startups |
| hackathon | |
| maker | makers, maker movement |
| open source | open-source |
| DIY | do-it-yourself |
| cottage industry | |

---

## 6. Production, Scaling & Industrial Terms

| Term | Variants |
|------|----------|
| production | mass production, drone production |
| manufacture | manufacturing, manufacturer(s) |
| assembly | assembly line |
| procurement | defense procurement |
| supply chain | supply chains, logistics |
| scale | scaling, scaled up, scale up |
| capacity | production capacity |
| factory | factories, drone factory |
| workshop | workshops |
| defense industry | defence industry |
| domestic production | |
| industrial base | industrial capacity |

---

## 7. Key Actors & Organizations

| Term | Notes |
|------|-------|
| Aerorozvidka | Volunteer aerial reconnaissance unit |
| Come Back Alive | Major Ukrainian volunteer organization |
| United24 | Ukrainian government fundraising platform |
| Brave1 | Ukrainian defense-tech accelerator |
| Army of Drones | Ukrainian government drone program |
| Ministry of Digital Transformation | Diia, Mykhailo Fedorov |
| Ukroboronprom | Ukrainian state defense conglomerate |
| General Staff | Ukrainian General Staff |
| Territorial Defense | TDF, territorial defense forces |
| DARPA | potential foreign collaboration references |
| NATO | |

---

## 8. Conflict Phases & Context

| Term | Variants |
|------|----------|
| Crimea | annexation |
| Donbas | Donetsk, Luhansk |
| full-scale invasion | full-scale war, escalation |
| counteroffensive | counter-offensive |
| frontline | front line, front lines |
| Kyiv | Kiev (alternative spelling) |
| Kherson | |
| Zaporizhzhia | |
| Bakhmut | |
| Black Sea | Black Sea Fleet |
| mobilization | mobilisation |
| attrition | attritional warfare |

---

## Recommended NLP Approach

> [!TIP]
> **Search strategy suggestions:**
> 1. **Case-insensitive matching** — ISW briefs may vary in capitalization
> 2. **Stemming/lemmatization** — Capture all morphological variants (e.g., "innovate," "innovation," "innovative")
> 3. **N-gram analysis** — Many key concepts are multi-word (e.g., "loitering munition," "electronic warfare")
> 4. **Temporal frequency tracking** — Chart term frequency over time to identify inflection points in unpiloted systems adoption
> 5. **Co-occurrence analysis** — Track which terms appear together to identify relationships (e.g., "FPV" + "volunteer")
> 6. **Categorized aggregation** — Aggregate frequencies by the categories above to track thematic trends (e.g., grassroots terms vs. industrial terms over time may reveal the scaling trajectory)

> [!IMPORTANT]
> The categories above are designed to align with the **Socio-Technical Transitions Framework** referenced in the study design:
> - **Categories 5–6** (grassroots + scaling) → niche innovation & regime transformation
> - **Categories 1–4** (systems + operations) → technological trajectory
> - **Categories 7–8** (actors + context) → landscape-level pressures and multi-level interactions
