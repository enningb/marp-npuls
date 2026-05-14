---
marp: true
theme: npuls
paginate: true
footer: Npuls · Huisstijl Demo
---

<!-- _class: cover -->

# Onderwijs bewegen.
## Titel van de presentatie

Naam spreker · Datum · Organisatie

---

# Standaard slide

De **standaard slide** heeft een witte achtergrond.
Koppen gebruiken de Npuls-accentkleur.

- Eerste bullet met **vetgedrukte** tekst
- Tweede punt met *cursief* (Cooper Light)
- Derde punt met `code snippet`

> Dit is een blockquote in Cooper Light.

---

## Twee kolommen

<div class="columns">
<div>

### Links
Gebruik `<div class="columns">` voor een 50/50 layout.

- Punt één
- Punt twee
- Punt drie

</div>
<div>

### Rechts

<div class="highlight">
Oranje callout-box voor aandachtspunten.
</div>

<div class="highlight-blue" style="margin-top:12px">
Blauwe callout voor informatie.
</div>

</div>
</div>

---

<!-- _class: section-title -->

# Hoofdstuk 1
## Vormentaal & Iconen

---

<!-- _class: vormentaal -->

# Vormentaal
## Cirkel-decoratie (rechtsonder)

De `vormentaal` klasse plaatst een grote oranje cirkel als
decoratief element in de rechterbenedenhoek.

- Subtiel en on-brand
- Varianten: `yellow-circle`, `blue-circle`, `green-circle`
- Positie: voeg `circle-left` toe voor linksboven

---

<!-- _class: vormentaal yellow-circle -->

# Vormentaal
## Gele cirkel-variant

Voeg `yellow-circle` toe aan de klasse:

```
<!-- _class: vormentaal yellow-circle -->
```

De vormentaal mogen in combinatie met elkaar
maar ook losstaand worden gebruikt.

---

<!-- _class: vormentaal-split -->

# Vormentaal Split
## Diagonale kleurband rechts

De `vormentaal-split` klasse voegt een diagonale
gele band toe aan de rechterzijde van de slide.

Varianten: `split-orange`, `split-blue`, `split-green`

---

<!-- _class: vormentaal-split split-blue -->

# Vormentaal Split
## Blauwe variant

```markdown
<!-- _class: vormentaal-split split-blue -->
```

Pas de diagonale band aan met een kleur-modifier.

---

<!-- _class: vormentaal-statement -->

# Hartslag voor beter onderwijs

## Een betrokken community

---

<!-- _class: vormentaal-statement statement-blue -->

# Het onderwijs vooruit helpen

## Npuls · Onderwijs bewegen.

---

<!-- _class: vormentaal-statement statement-yellow -->

# Een betrokken community

## Verbinden. Inspireren. Organiseren.

---

<!-- _class: vormentaal-circles -->

# Vormentaal Cirkels
## Gekleurde stippen als decoratie

De `vormentaal-circles` klasse plaatst een groep
gekleurde cirkels rechtsboven — gebaseerd op
het Npuls kleurenpalet.

Combineer met inhoudelijke tekst of iconen.

---

<!-- _class: vormentaal-frame -->

# Vormentaal Frame
## Geometrisch hoekaccent

De `vormentaal-frame` klasse voegt een subtiel
oranje L-haak toe in de rechterbovenhoek —
een geometrisch ankerpunt.

---

# Inline shape-bar

Gebruik `<div class="shape-bar">` voor tekst op een gekleurde balk:

<div class="shape-bar">Hartslag voor beter onderwijs</div>

<div class="shape-bar blue">Een betrokken community</div>

<div class="shape-bar yellow">Het onderwijs vooruit helpen</div>

<div class="shape-bar green">Verbinden. Inspireren.</div>

---

# Decoratieve punten

Gebruik `<span class="dot">` als kleuraccent in tekst of als scheider:

<span class="dot orange xlarge"></span>
<span class="dot blue xlarge"></span>
<span class="dot yellow xlarge"></span>
<span class="dot green xlarge"></span>

<div class="dot-rule"></div>

Gebruik `<div class="dot-rule">` als een branded horizontale lijn.

---

<!-- _class: section-title -->

# Hoofdstuk 2
## Iconen

---

# Iconen — FontAwesome Solid

Gebruik `<i class="fa-solid fa-naam">` voor inline iconen:

<i class="fa-solid fa-graduation-cap fa-2x icon-orange"></i>  Leren
&nbsp;&nbsp;
<i class="fa-solid fa-users fa-2x icon-blue"></i>  Samenwerken
&nbsp;&nbsp;
<i class="fa-solid fa-lightbulb fa-2x icon-yellow"></i>  Innoveren
&nbsp;&nbsp;
<i class="fa-solid fa-chart-line fa-2x icon-green"></i>  Groeien

<br>

> Het Npuls merk gebruikt FontAwesome **Sharp Solid** (FA6 Pro).
> Dit thema laadt FA6 **Solid** (gratis) als naaste alternatief.

---

# Icon Cards — drie kolommen

<div class="columns-3">
<div class="icon-card icon-orange">
<i class="fa-solid fa-sitemap fa-3x"></i>
<strong>Organiseren</strong>
<p>Structuur bieden aan de onderwijsgemeenschap.</p>
</div>
<div class="icon-card icon-blue">
<i class="fa-solid fa-link fa-3x"></i>
<strong>Verbinden</strong>
<p>Mensen en initiatieven samenbrengen.</p>
</div>
<div class="icon-card icon-green">
<i class="fa-solid fa-rocket fa-3x"></i>
<strong>Inspireren</strong>
<p>Het onderwijs in beweging brengen.</p>
</div>
</div>

---

# Icon Rows — lijst met iconen

<div class="icon-row icon-orange">
<i class="fa-solid fa-check-circle"></i> Eerste aandachtspunt of kenmerk
</div>
<div class="icon-row icon-blue">
<i class="fa-solid fa-circle-info"></i> Tweede informatieve bullet
</div>
<div class="icon-row icon-green">
<i class="fa-solid fa-star"></i> Derde succesfactor of resultaat
</div>
<div class="icon-row icon-yellow">
<i class="fa-solid fa-lightbulb"></i> Vierde tip of aanbeveling
</div>

---

<!-- _class: section-title -->

# Hoofdstuk 3
## Kleurvarianten

---

<!-- _class: dark -->

# Dark slide

Op een **donkere achtergrond** springen de merkkleuren goed uit.

<div class="icon-row icon-orange"><i class="fa-solid fa-fire"></i> Oranje accentkleur voor h1 en bullets</div>
<div class="icon-row icon-yellow"><i class="fa-solid fa-sun"></i> Geel voor h2 en vetgedrukte tekst</div>
<div class="icon-row icon-blue"><i class="fa-solid fa-water"></i> Lichtblauw voor h3 en links</div>

---

<!-- _class: blue -->

# Blue slide
## Gele accenten op blauw

<div class="columns">
<div>

<span class="tag tag-yellow">Nieuw</span>
<span class="tag">Feature</span>

Blauwe slides werken goed als tussenslides of
secties die extra nadruk verdienen.

</div>
<div>

<div class="icon-card icon-yellow">
<i class="fa-solid fa-bolt fa-3x"></i>
<strong>Impact</strong>
<p>Direct zichtbaar verschil maken.</p>
</div>

</div>
</div>

---

<!-- _class: green -->

# Green slide
## Voor succes en milestones

<div class="columns">
<div>

<div class="icon-row"><i class="fa-solid fa-trophy icon-yellow"></i> Resultaat bereikt</div>
<div class="icon-row"><i class="fa-solid fa-chart-line icon-yellow"></i> Groei zichtbaar</div>
<div class="icon-row"><i class="fa-solid fa-handshake icon-yellow"></i> Samenwerking geslaagd</div>

</div>
<div>

<div class="shape-bar yellow">Gelukt!</div>

</div>
</div>

---

<!-- _class: yellow -->

# Yellow slide
## Attentie of highlight-moment

Gele achtergrond trekt de aandacht.
Gebruik spaarzaam voor de sterkste impact.

<span class="tag tag-blue">Let op</span>
<span class="tag tag-black">Actie vereist</span>

---

<!-- _class: quote -->

> Onderwijs bewegen
> begint met één stap.

---

<!-- _class: cover -->

# Bedankt!

**Naam** · functie@npuls.nl · npuls.nl

Onderwijs bewegen.
