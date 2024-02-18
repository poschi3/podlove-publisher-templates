# Podlove-Publisher Templates

Podlove-Publisher Templates die wir für den [Entbehrliches-Podcast](https://podcast.entbehrlich.es/) verwenden.

## Benutzung

* Template erzeugen
  * Im Wordpress Admin-Bereich auf `Podlove` -> `Templates` gehen
  * Auf `+ Neues Template erstellen` klicken
  * Namen vergeben (z. B. `statistik`)
  * Inhalt der twig-Datei (z. b. `statistik.twig` in das Templates kopieren
  * Template an den eigenen Podcast anpassen
  * Speichern

  ![grafik](https://user-images.githubusercontent.com/825911/121785979-604f4f80-cbbd-11eb-98c8-edd852db884b.png)

* Einbinden
  * Wordpress Seite erzeugen (z. B. `Statistik`)
  * Template mittels Shortcode (z.B. `[podlove-template template="statistik"]`) einfügen
  * Speichern

  ![grafik](https://user-images.githubusercontent.com/825911/121785992-778e3d00-cbbd-11eb-82ba-efcb1e485198.png)

* Ausprobieren

Weite Infos in der [Podlove-Publisher Doku](https://docs.podlove.org/podlove-publisher/guides/templates).

## Templates

### Statistik ([Demo](https://podcast.entbehrlich.es/statistik/))

Statistik über Downloads und Folgenlängen

![grafik](https://user-images.githubusercontent.com/825911/121786046-c76d0400-cbbd-11eb-8c35-2c941e530a2d.png)

### Archiv ([Demo](https://podcast.entbehrlich.es/archiv/))

Seite mit allen Folgen, gruppiert nach Jahr
