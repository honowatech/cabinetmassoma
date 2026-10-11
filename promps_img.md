# Prompts des images — Page d'accueil Cabinet Massoma

Direction artistique commune à toutes les images :
- **Palette** : encre profonde `#0C1620`, vert-bleu du Wouri `#1F4E52`, laiton `#C9A46A`, ivoire `#F5F0E6`.
- **Ambiance** : éditoriale, sobre, lumière naturelle rasante (golden hour ou fin de journée), grain argentique léger, profondeur de champ maîtrisée.
- **À éviter** : clichés de stock (marteaux de juge, balances en plastique, poignées de main posées), texte incrusté, logos, visages reconnaissables de personnes réelles.
- **Format de livraison** : WebP + JPG, qualité 80, aux dimensions indiquées (prévoir aussi une version @2x pour le héros).

---

## 1. Héros — Cour d'Appel de Bonanjo
- **Emplacement** : section Héros, image en arche (colonne de droite)
- **Fichier** : `hero-cour-appel-bonanjo.webp` — **900 × 1200** (portrait 3:4)
- **Alt** : Façade de la Cour d'Appel à Bonanjo, Douala, au coucher du soleil

> Architectural photograph of a colonial-era courthouse facade in Bonanjo, Douala, Cameroon, tall white columns and arched windows, warm golden-hour light raking across the stone, deep teal-navy evening sky, a few palm fronds framing the edge, low-angle view emphasizing authority and permanence, quiet and empty street, cinematic, editorial magazine style, subtle film grain, muted palette of deep navy, teal and brass-gold highlights, portrait 3:4, no people, no text.

---

## 2. Carte « Audit Social »
- **Emplacement** : section Expertises, carte 01
- **Fichier** : `expertise-audit-social.webp` — **800 × 600** (4:3)
- **Alt** : Auditeur social analysant des registres du personnel

> Close-up editorial photo of a lawyer's hands reviewing HR documents, payroll ledgers and a printed audit checklist on a dark walnut desk, a brass fountain pen and reading glasses, soft window light from the left, shallow depth of field, a Black African professional in a tailored navy suit (face not visible), calm and meticulous atmosphere, color grading in deep teal and warm brass tones, subtle film grain, 4:3, no readable text.

---

## 3. Carte « Conseil »
- **Emplacement** : section Expertises, carte 02
- **Fichier** : `expertise-conseil.webp` — **800 × 600** (4:3)
- **Alt** : Réunion de conseil juridique entre un avocat et des dirigeants

> Elegant boardroom scene in a modern law office in Douala, three African executives and a senior lawyer in discussion around a dark wood table, seen from behind and in soft focus so faces are not identifiable, floor-to-ceiling windows with the city blurred beyond, late afternoon golden light, leather portfolios and bound legal codes on the table, sophisticated, discreet, international law firm aesthetic, deep navy and brass color grading, 4:3, no text.

---

## 4. Carte « Droit Maritime »
- **Emplacement** : section Expertises, carte 03
- **Fichier** : `expertise-droit-maritime.webp` — **800 × 600** (4:3)
- **Alt** : Navire porte-conteneurs à quai au port de Douala

> Large container ship moored at the Port of Douala on the Wouri estuary at dusk, gantry cranes silhouetted against a gradient sky from deep navy to warm amber, calm water reflecting the lights, stacked containers in muted tones, wide composition with strong horizontal lines, documentary yet premium editorial style, teal and brass color grading, subtle film grain, 4:3, no visible brand names or text.

---

## 5. A Propos — Bibliothèque du cabinet
- **Emplacement** : section A Propos, colonne gauche (sticky)
- **Fichier** : `apropos-bibliotheque.webp` — **800 × 1000** (4:5)
- **Alt** : Bibliothèque juridique du cabinet avec codes OHADA et ouvrages de droit

> Interior of a refined private law library, floor-to-ceiling dark wood shelves filled with leather-bound law books and legal codes, a reading table with a green-shaded brass banker's lamp glowing, an open book and a brass seal stamp, warm low light, deep navy walls, quiet and scholarly atmosphere, editorial interior photography, shallow depth of field, brass and teal tones, portrait 4:5, no readable text on spines.

---

## 6. Bandeau « Douala ⟷ Paris »
- **Emplacement** : bandeau pleine largeur entre A Propos et Domaines (affichée à 40 % d'opacité sous un dégradé encre)
- **Fichier** : `bandeau-douala-paris.webp` — **1920 × 900** (panoramique)
- **Alt** : Vue panoramique de l'estuaire du Wouri et du pont sur le Wouri à Douala au crépuscule

> Wide panoramic aerial view of the Wouri estuary and the Wouri bridge in Douala, Cameroon, at blue hour, city lights beginning to glow along the riverbanks, long exposure smoothing the water, mangroves in the foreground darkness, vast sky gradient from deep navy to a thin line of brass-gold on the horizon, cinematic and serene, large negative space on the left side for text overlay, muted teal and gold palette, 1920x900, no text.

---

## 7. Image de partage (Open Graph / réseaux sociaux)
- **Emplacement** : balises `og:image` et `twitter:image`
- **Fichier** : `og-cabinet-massoma.jpg` — **1200 × 630**
- **Alt** : Cabinet Massoma — Avocats Conseil - Auditeur Social, Douala

> Minimalist premium brand visual, deep ink-navy background with subtle paper grain, a refined brass-gold monogram "M" inscribed in a thin double circle on the left third, generous negative space on the right for the title "Cabinet Massoma" set in an elegant high-contrast serif (to be added in post-production), faint vertical guide lines like a legal document grid, soft brass light gradient from the top right corner, luxury international law firm identity, 1200x630.

---

## Remplacement dans le code

Chaque image utilise actuellement une URL `https://placehold.co/...`. Une fois les visuels produits, remplacer l'attribut `src` par le chemin du fichier (ex. `/assets/img/hero-cour-appel-bonanjo.webp`) en conservant les attributs `width`, `height`, `alt` et `loading` déjà en place.

---
---

# Page « Audit Social » (`audit-social.html`)

Même direction artistique que la page d'accueil. Les sujets doivent évoquer **rigueur, examen, terrain et confidentialité**, sans cliché de stock (pas de loupe sur un document, pas de checklists cochées en gros plan).

## 8. Héros — Audit Social
- **Emplacement** : héros de la page, colonne de droite (cadre laiton)
- **Fichier** : `audit-social-hero.webp` — **1000 × 1200** (portrait 5:6)
- **Alt** : Auditeur social examinant des dossiers du personnel dans une salle d'archives d'entreprise

> Editorial photograph inside a corporate archive room in Douala, tall metal shelving with neatly labelled personnel files in muted kraft and navy folders, a senior African auditor in a tailored dark suit seen from three-quarter back, pulling a file from a shelf, a single shaft of warm late-afternoon light crossing the room, dust particles visible in the light, deep navy shadows and brass highlights, calm, methodical, discreet atmosphere, shallow depth of field, subtle film grain, portrait 5:6, no readable text, face not identifiable.

## 9. Méthodologie — Entretiens sur site
- **Emplacement** : section Méthodologie, colonne gauche (desktop)
- **Fichier** : `audit-social-entretiens.webp` — **800 × 600** (4:3)
- **Alt** : Entretien d'audit social conduit sur un site industriel avec un responsable des ressources humaines

> Two professionals in conversation in a glass-walled meeting room overlooking an industrial or port facility in Cameroon, one taking notes in a leather notebook, safety helmets resting on the table, cranes and warehouses softly blurred through the window, overcast natural light, documentary yet premium corporate style, teal and brass color grading, faces turned away or out of focus, 4:3, no text, no logos.

## 10. Pourquoi le Cabinet Massoma — Avocat & auditeur
- **Emplacement** : section « La double compétence avocat-auditeur », colonne gauche
- **Fichier** : `audit-social-avocat.webp` — **800 × 1000** (4:5)
- **Alt** : Avocat du Cabinet Massoma relisant un rapport d'audit social dans son bureau de Bonanjo

> Refined lawyer's office at dusk, a bound audit report with a brass binding clip on a dark walnut desk, a fountain pen, reading glasses and a cup of black coffee, an African lawyer's hands turning a page (face out of frame), shelves of legal codes in soft focus behind, window with the warm glow of Douala's Bonanjo district, low-key lighting, deep navy and brass palette, editorial, quiet authority, portrait 4:5, no readable text.

## 11. Image de partage — Audit Social
- **Emplacement** : `og:image` / `twitter:image` de la page
- **Fichier** : `og-audit-social.jpg` — **1200 × 630**
- **Alt** : Audit Social — Cabinet Massoma

> Minimal premium visual, deep teal (#1F4E52) background with subtle paper grain, a thin brass-gold 3x3 grid (evoking a risk matrix) on the right third with one cell filled in brass, the Massoma "M in a circle" monogram small in the top-left corner, generous negative space on the left for the title "Audit Social" in an elegant high-contrast serif (added in post-production), luxury international law firm identity, 1200x630.
