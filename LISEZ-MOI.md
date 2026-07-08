# RORO NELA — ARABIA · Livrables (sortie 17 juillet 2026)

Trois pièces qui partagent la même direction artistique (vert profond + or, calligraphie de la cover provisoire, polices Marcellus / Cormorant / Jost / Amiri).

## Contenu du dossier
```
Roronella-Arabia-Livrables/
├── index.html          → Présentation-site FR/EN (le HUB : écoute du master, YouTube, stratégie)
├── kit-presse.html     → Kit de presse FR/EN (cover, univers, bio, prises de parole, réseaux)
├── cover-animee.html   → Cover animée (annonce du 17 juillet, format carré 1:1)
├── LISEZ-MOI.md        → ce fichier
└── assets/
    ├── Arabia-Master-Final4.m4a   ← le master final (Wave 4), 3:38, intégré au lecteur
    ├── cover-provisoire.jpg
    ├── emblem-olivier.png
    ├── photo-desert.jpg / photo-blanc.jpg
    └── photos/ (hero, band, blanc, désert…)
```

## 1. Voir tout de suite
Ouvre **index.html** dans un navigateur (double-clic). En haut à droite : bouton **FR / EN**. Le titre se lit directement dans le lecteur (master final).
- `index.html` renvoie vers `kit-presse.html` et `cover-animee.html`.

## 2. En faire UN LIEN à envoyer (gratuit, sans compte)
1. Va sur **app.netlify.com/drop**
2. Glisse-dépose **tout le dossier** `Roronella-Arabia-Livrables` (pas seulement un fichier — le dossier, pour garder l'audio et les images).
3. Tu obtiens en ~15 s une adresse publique (ex. `https://xxxx.netlify.app`). L'accueil sera `index.html`.
   - Kit de presse : `…netlify.app/kit-presse.html` · Cover animée : `…netlify.app/cover-animee.html`
Équivalents : Vercel, Cloudflare Pages, GitHub Pages.

## 3. Ajouter le lien YouTube
Dans `index.html`, section « Écouter », le bouton **Regarder sur YouTube** pointe pour l'instant vers la chaîne `@roro_nela`. Une fois la vidéo/visualizer en ligne, remplace le lien : cherche `id="ytLink"` (une seule ligne, commentaire `▼ Remplacer le href…`) et colle l'URL de la vidéo.

## 4. La cover animée — options & export
`cover-animee.html` : **l'animation tourne en boucle** (~10 s) et **redémarre à chaque changement de version** (titre/phase/format). Le son se lance avec le gros bouton doré **🔊 Écouter l'extrait du master** (saute au refrain, fondu de volume, égaliseur animé quand ça joue — un clic est obligatoire, les navigateurs bloquent l'autoplay sonore). Boutons :
- **Avec titre / Sans titre** — version avec le mot ARABIA + accroche, ou visuel épuré (juste l'artiste + la date).
- **Teaser · 17 juil. / Jour J · Dispo** — « Sortie le 17 juillet 2026 » ou « Disponible maintenant » (à utiliser le jour J).
- **Carré 1:1 / Story 9:16** — les deux formats réseaux.
- **⬇︎ Télécharger le visuel (PNG)** — exporte le visuel **fixe** en 1080×1080 (ou 1080×1920), avec ou sans titre selon le réglage. *(L'export marche une fois le dossier publié sur Netlify ; en local `file://` certains navigateurs le bloquent → publie d'abord, ou fais une capture d'écran.)*

**Pour une VIDÉO** : format conseillé **MP4 (H.264) · 1080×1080 · ~8 s en boucle** (feed) ou **1080×1920** (stories/reels). Lance un **enregistrement d'écran** (⌘⇧5 sur Mac) sur la zone du visuel, laisse tourner ~2 boucles, recadre.

## 5. Ce qui est déjà dans la présentation
- **Paroles & traductions** (عربية · Français · English) juste au-dessus de l'écoute — *structure prête, à remplir* : il me faut le **texte réel des paroles** (en arabe, ou une transcription) pour les traduire mot pour mot fidèlement. Je n'invente pas de paroles. Repère `id="paroles-chanson"` dans `index.html`.
- **Écoute du master final** (Wave 4) intégrée + bouton YouTube + pré-save (à activer).
- **Bio courte** multi-origines (née libanaise, a grandi entre le Liban, la République tchèque et Dubaï, aujourd'hui France/Europe).
- **Le message d'Arabia** : récit reconstruit à partir de ses mots de l'ancien kit (« une déclaration d'amour, de fierté et d'unité », « aucune honte à être arabe… il faut en être fier », « j'ai grandi entre ces deux mondes… une manière de les réunir », l'oud & les percussions).
- **Rétro-planning** (frise) : Teasers & mini-visuels (avant le 17) → **Jour J 17 juillet** (sortie du single + vague de visuels réseaux) → **Semaine du 20 juillet : le clip** (tourné au Liban, réal. Tareck Raffoul) → **En continu** (créer un monde autour de Roro Nela : covers, mini-visuels, campagne radios & communauté).
- Le kit ajoute une section **Reconnaissance & presse** (Radio Monte Carlo Doualiya, Musivv Awards, direction visuelle Tareck Raffoul, citation presse).
- **Stratégie de lancement** — créer un monde autour de Roro Nela : (1) un maximum de **contenus réseaux** (vidéos, covers, mini-visuels) autour de la musique et de son univers ; (2) **campagne radios** (mails aux radios concernées & communautaires, RDV, interviews — Radio Orient, Beur FM, RMC Doualiya, web-radios orientales) ; (3) **communauté libanaise & milieux culturels arabes** (France & monde) — trouver les bons contacts pour un plan d'action dès la sortie ; (4) contacts communautaires en France (IMA, ULCM, HALFA, RJLiban, Cèdre sur Seine).

## 6. Version PDF propre (pages bien coupées)
Chaque page a une **feuille de style d'impression** : ouvre le fichier → **Imprimer → Enregistrer en PDF**. Les cartes et paragraphes ne se coupent pas entre deux pages, les fonds/couleurs sont conservés, et les barres de navigation sont masquées.

## Notes
- Noms d'associations, radios, salles et festivals = **pistes de travail** à confirmer/prioriser selon les contacts.
- Textes arabes (عربية) à faire valider par un locuteur natif.
- Ligne rouge respectée partout : **« une lumière, pas un camp »** — jamais de politique, jamais d'images de guerre comme décor.

Contact : AZODER · Amos Bosse — azoderconsulting@gmail.com — www.azoder.fr
