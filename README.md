# Gerenuk Bot Dokumentation

## Inhaltsverzeichnis

- [Anmeldung am Server](#anmeldung-am-server)
  - [Befehl: Neustart der Anmeldung](#befehl-anmeldung_neustarten)
  - [Befehl: Schüler verifizieren](#befehl-schüler_verifizieren)

- [Chat löschen](#chat-löschen)
  - [Befehl: Chat löschen](#befehl-chat_löschen)

- [Abwesenheiten](#abwesenheiten)
  - [Befehl: Abwesenheit eintragen](#befehl-abwesenheit-eintragen)
  - [Befehl: Abwesenheit austragen](#befehl-abwesenheit-austragen)
  - [Befehl: Tabelle aller Abwesenheiten](#befehl-abwesenheit-tabelle)

- [Musikbot (Youtube, Spotify, Radio)](#musikbot-youtube-spotify-radio)
  - [Befehl: Musikkanal beitreten](#befehl-join)
  - [Befehl: Musikkanal verlassen](#befehl-leave)
  - [Befehl: Spotify-Playlist laden](#befehl-load_spotify)
  - [Befehl: Musik abspielen](#befehl-musik_play)
  - [Befehl: Musik stoppen](#befehl-musik_stop)
  - [Befehl: Musik suchen](#befehl-musik_suche)
  - [Befehl: YouTube-Playlist](#befehl-youtube_playlist)
  - [Befehl: Playlist anzeigen](#befehl-show_playlist)
  - [Befehl: Lied überspringen](#befehl-skip)
  - [Befehl: Playlist mischen](#befehl-shuffle_playlist)
  - [Befehl: Radiosenderliste](#befehl-radio_list)
  - [Befehl: Radiosender abspielen](#befehl-radio_play)

- [Webuntis](#webuntis)
  - [Befehl: Aktuelle Unterrichtsstunde](#befehl-webuntis_aktuell)
  - [Befehl: Unterrichtsfächer für ein bestimmtes Datum](#befehl-webuntis_datum)
  - [Befehl: Klassenraum suchen](#befehl-webuntis_wo)

## Anmeldung am Server<a name="anmeldung-am-server"></a>

### Befehl: Neustart der Anmeldung<a name="befehl-anmeldung_neustarten"></a>

```
/anmeldung_neustarten
```

Erklärung: Dieser Befehl ermöglicht den Neustart der Anmeldung am Server, sollte der Schüler den Neustart abgebrochen haben.



### Befehl: Schüler verifizieren<a name="befehl-schüler_verifizieren"></a>

```
/schüler_verifizieren benutzer_id:benutzerid benutzername:benutzername
```

Erklärung: Mit diesem Befehl können Schüler verifiziert werden.

<font color="red">Warnung:</font> Dieser Befehl sollte und kann nur von Moderatoren, Admins, Tech-Support oder Klassensprechern verwendet werden.

<font color="red">Information:</font> Klassensprecher können nur Schüler aus der eigenen Klasse verifizieren, Admins und Moderatoren hingegen aus jeder Klasse.

Parameter:
- benutzer_id: Die Benutzer-ID des zu verifizierenden Nutzers z.B 760121326618411019
- benutzername: z.B el_rolando

<font color="red">Warnung:</font> Es darf entweder der Parameter benutzer_id oder der Parameter benutzername verwendet werden.



## Chat löschen<a name="chat-löschen"></a>

### Befehl: Chat löschen<a name="befehl-chat_löschen"></a>

```
/chat_löschen
```

Erklärung: Löscht alle Kommunikationen mit dem Bot.


## Abwesenheiten<a name="abwesenheiten"></a>

### Befehl: Abwesenheit eintragen<a name="befehl-abwesenheit-eintragen"></a>

```
/abwesenheit_eintragen
```

Erklärung: Dieser Befehl ermöglicht es dem User, seine Abwesenheit einzutragen

### Befehl: Abwesenheit austragen<a name="befehl-abwesenheit-austragen"></a>

```
/abwesenheit_austragen
```

Erklärung: Dieser Befehl ermöglicht es dem User, seine Abwesenheit auszutragen

### Befehl: Abwesenheit austragen<a name="befehl-abwesenheit-tabelle"></a>

```
/abwesenheit_tabelle
```

Erklärung: Der Bot schickt eine Tabelle mit allen Personen, die krank sind hinein.
Diese Tabelle beinhaltet folgendes:
- Name
- Klasse


## Musikbot (Youtube, Spotify, Radio)<a name="musikbot-youtube-spotify-radio"></a>

### Befehl: Musikkanal beitreten<a name="befehl-join"></a>

```
/join
```

Erklärung: Mit diesem Befehl kann der Bot dem Sprachkanal beitreten. Der Bot wird den Sprachkanal beitreten, in der der Benutzer aktuell ist.

<font color="red">Warnung:</font> Der Bot kann nicht in 2 Kanälen gleichzeitig sein. Der Bot kann durch Verlassen und wieder-beitreten in einen anderen Kanal verschoben werden.




### Befehl: Musikkanal verlassen<a name="befehl-leave"></a>

```
/leave
```

Erklärung: Dieser Befehl ermöglicht es dem Bot, den Sprachkanal zu verlassen.



### Befehl: Spotify-Playlist laden<a name="befehl-load_spotify"></a>

```
/load_spotify playlist_url:playlist
```

Erklärung: Mit diesem Befehl kann eine Spotify-Playlist geladen werden.

Parameter: 
- playlist_url: Die URL der Playlist, z.B. https://open.spotify.com/playlist/37i9dQZF1DZ06evO05tE88

### Befehl: Musik abspielen<a name="befehl-musik_play"></a>

```
/musik_play url:youtubeurl
```

Erklärung: Dieser Befehl spielt Musik von einer YouTube-URL ab.

Parameter: 
- url: Die URL des Videos, z.B. https://www.youtube.com/watch?v=dQw4w9WgXcQ

### Befehl: Musik stoppen<a name="befehl-musik_stop"></a>

```
/musik_stop
```

Erklärung: Mit diesem Befehl kann die Musikwiedergabe gestoppt werden.


### Befehl: Musik suchen<a name="befehl-musik_suche"></a>

```
/musik_suche anfrage:anfrage
```

Erklärung: Dieser Befehl ermöglicht die Suche nach Musik auf YouTube.
Der Bot antwortet danach mit den Suchanfragen. Der User kann dann mit einer Zahl antworten und dann wird das Video/die Musik abgespielt

Parameter: 
- anfrage: Die Suchanfrage, z.B Álvaro Soler - Sofia

### Befehl: YouTube-Playlist<a name="befehl-youtube_playlist"></a>

```
/youtube_playlist playlist_url:playlist_url
```

Erklärung: Mit diesem Befehl kann eine YouTube-Playlist verwaltet werden.

Parameter: 
- playlist_url: Die URL der Playlist, zum Beispiel 

### Befehl: Playlist anzeigen<a name="befehl-show_playlist"></a>

```
/show_playlist
```

Erklärung: Dieser Befehl zeigt die aktuelle Playlist an.

Parameter: Hier kommen die Parameter hin.

### Befehl: Lied überspringen<a name="befehl-skip"></a>

```
/skip
```

Erklärung: Mit diesem Befehl kann ein Lied in der Playlist übersprungen werden.

Parameter: Hier kommen die Parameter hin.

### Befehl: Playlist mischen<a name="befehl-shuffle_playlist"></a>

```
/shuffle_playlist
```

Erklärung: Dieser Befehl mischt die Playlist.

Parameter: Hier kommen die Parameter hin.

### Befehl: Radiosenderliste<a name="befehl-radio_list"></a>

```
/radio_list
```

Erklärung: Mit diesem Befehl kann die Liste der verfügbaren Radiosender angezeigt werden.
Derzeit unterstützt: 
1. Rádio 1 89.5 Budapest (Ungarn)
2. Ö3 (Österreich)
3. Radio Burgenland (Burgenland, Österreich)

### Befehl: Radiosender abspielen<a name="befehl-radio_play"></a>

```
/radio_play radio_position:position radio_name:name
```

Erklärung: Dieser Befehl spielt einen Radiosender ab.

Parameter: 
- radio_name: Der Name des Radios. Derzeit werden folgende unterstützt. Rádio 1, Ö3, Radio Burgenland
- radio_position: Die Position des Radios in der Radioliste. Derzeit 1-3.

<font color="red">Warnung:</font> Es kann entweder der Parameter radio_name oder der Parameter radio_position verwendet werden.

## Webuntis<a name="webuntis"></a>

### Befehl: Aktuelle Unterrichtsstunde<a name="befehl-webuntis_aktuell"></a>

```
/webuntis_aktuell
```

Erklärung: Der Bot antwortet mit dem Unterricht, der gerade stattfindet, auch mit Angaben zum Raum.



### Befehl: Unterrichtsfächer für ein bestimmtes Datum<a name="befehl-webuntis_datum"></a>

```
/webuntis_datum datum:TT.MM.JJJJ
```

Erklärung: Der Bot antwortet mit allen Unterrichtsfächern für diesen Tag, inkl. Raum.

Parameter:
- datum: Datum, im Format TT.MM.JJJJ, zum Beispiel: 10.10.2023

### Befehl: Klassenraum suchen<a name="befehl-webuntis_wo"></a>

```
/webuntis_wo klassenraum:Klassenraum
```

Erklärung: Der Bot antwortet mit der Information, wo sich der Raum befindet

Parameter:
- klassenraum: Der Name des Klassenraums, zum Beispiel: 6A

