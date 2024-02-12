# Gerenuk Bot Dokumentation

## Inhaltsverzeichnis



- [Chat löschen](#chat-löschen)
  - [Befehl: Chat löschen](#befehl-chat_löschen)

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

- [Spiele](#spiele)
  - [Befehl: Tic Tac Toe spielen](#befehl-tictactoe)

<!--- - [Webuntis](#webuntis)
  - [Befehl: Aktuelle Unterrichtsstunde](#befehl-webuntis_aktuell)
  - [Befehl: Unterrichtsfächer für ein bestimmtes Datum](#befehl-webuntis_datum)
  - [Befehl: Klassenraum suchen](#befehl-webuntis_wo) -->


## Chat löschen<a name="chat-löschen"></a>

### Befehl: Chat löschen<a name="befehl-chat_löschen"></a>

```
/chat_löschen
```

Erklärung: Löscht alle Kommunikationen mit dem Bot.



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
1. Rádió 1 89.5 (Budapest, Ungarn)
2. Radio Burgenland (Österreich)
3. Ö3 (Österreich)
4. Retró Radió (Ungarn)

### Befehl: Radiosender abspielen<a name="befehl-radio_play"></a>

```
/radio_play radio_position:position radio_name:name
```

Erklärung: Dieser Befehl spielt einen Radiosender ab.

Parameter: 
- radio_name: Der Name des Radios. Derzeit werden folgende unterstützt. Rádio 1, Ö3, Radio Burgenland
- radio_position: Die Position des Radios in der Radioliste. Derzeit 1-3.

<font color="red">Warnung:</font> Es kann entweder der Parameter radio_name oder der Parameter radio_position verwendet werden.

<!---
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
-->

## Spiele <a name="spiele"></a>

### Befehl: Tic Tac Toe spielen<a name="befehl-tictactoe"></a>

```
/tictactoe
```

Erklärung: Der Bot startet eine Spielrunde Tic-Tac-Toe
