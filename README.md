# Makerswiel Eindhoven

Makerswiel is een samenwerkingsverband van vrijwilligersgedreven tech-initiatieven in en om Eindhoven.

## Over Makerswiel


Makerswiel is een samenwerkingsverband van vrijwilligersgedreven tech-initiatieven in en om Eindhoven.
Makerswiel bestaat uit verschillende initatieven, die samen voor iedereen die iets met technologie wil doen in eindhoven kan bedienen! 
Er zijn plekken voor kinderen en volwassenen, voor een enkel bezoek tot meerder dagen in de week open. Wil je meer weten? Kijk dan naar de paginas van de losse groepen!

Ook zijn al deze initatieven vrijwilligersgedreven, en zijn nieuwe vrijwilligers welkom!


## Website

Deze repository bevat de broncode voor de [Makerswiel website](https://makerswiel.github.io). De site is gebouwd met Jekyll en wordt gehost op GitHub Pages.

### Lokaal ontwikkelen

Om de website lokaal te draaien:

1. Clone deze repository
   ```bash
   git clone https://github.com/makerswiel/makerswiel.github.io.git
   cd makerswiel.github.io
   ```

2. Installeer Jekyll en bundler gems
   ```bash
   gem install jekyll bundler
   bundle install
   ```

3. Run de development server
   ```bash
   bundle exec jekyll serve
   ```

4. Open `http://localhost:4000` in je browser

Je kunt nu wijzigingen maken aan de site en deze direct zien in je browser. De server ververst automatisch wanneer je bestanden opslaat.

#### Nieuw sidebar item maken

1. Maak een nieuw bestand aan in de `_posts` map
2. Gebruik de bestandsnaam: `YYYY-MM-DD-titel.md`
3. Begin het bestand met front matter:
   ```
   ---
   layout: post
   title: "Titel van je post"
   date: YYYY-MM-DD
   ---
   ```
4. Schrijf je content in Markdown onder de front matter

## Licentie

CC-BY