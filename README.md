# Terminal-Wetter

Schreib ein Terminal-Programm, das das Wetter für eine Stadt anzeigen kann. Es sollte als Parameter den Namen der Stadt annehmen. Um die Wetter-Info zu laden, kannst du die [`OpenWeather`](https://openweathermap.org/guide)-API benutzen.

-   Nutze `axios`. Richte dafür deinen eigenen `API KEY` ein.

-   So sollte die Ausgabe sein:

```bash
$ node src/index.js berlin
It is now 18.89°C in Berlin, DE
The current weather conditions are: few clouds
```

**Bonus**

-   Dein Programm soll die Wettervorhersage für die nächsten fünf Tage anzeigen
-   Dein Programm soll die Temperatur auch in Fahrenheit anzeigen können.
