# Clock Visualization - Configurable Rings

Dieses Repository enthält eine anpassbare Uhr, die mithilfe von **dynamischen farbigen Ringen** Sekunden, Minuten und Stunden visualisiert. Die Idee entstand aus einer Anfrage eines Freundes und ist für alle zugänglich – unter der **DBAD License**. 😉

## 🕒 Demo-Links
Schau dir die verschiedenen Versionen der Uhr an:
- [Demo 1](https://volkansah.github.io/clock/index.html)
- [Demo 2](https://volkansah.github.io/clock/index2.html)
- [Demo 3](https://volkansah.github.io/clock/index3.html)
- [Demo 4](https://volkansah.github.io/clock/index4.html)
- [Demo 5](https://volkansah.github.io/clock/index5.html)
- [Demo 6](https://volkansah.github.io/clock/index6.html)
- [Demo 7](https://volkansah.github.io/clock/index6.html) - **Beetlejuice**

## ⚙️ Konfiguration

Die Ringe der Uhr sind vollständig anpassbar. Hier ist die aktuelle Farbpalette:

```javascript
const clockConfig = {
    secondsRing: {
        outer: 100, // Ring anfang
        inner: 70,  // Ring ende
        segments: 60,
        activeColor: '#FF6F61', // Korallenrot
        inactiveColor: '#FFE4E1' // Leichtes Rosa
    },
    minutesRing: {
        outer: 70,  // Ring anfang
        inner: 50,  // Ring ende
        segments: 60,
        activeColor: '#6FCF97', // Pastellgrün
        inactiveColor: '#E8F5E9' // Blasses Grün
    },
    hoursRing: {
        outer: 50,  // Ring anfang
        inner: 40,  // Ring ende
        segments: 12, // Stunden
        activeColor: '#56CCF2', // Helles Blau
        inactiveColor: '#E3F2FD' // Blasses Himmelblau
    }
};
```
### 🧑‍💻 Beiträge

**Dieses Projekt wurde für einen Freund erstellt, ist aber für jeden zugänglich.** 
Beachte bitte: Dieses Projekt steht unter der DBAD License. 🛡️
Was ist die DBAD License? [Link](https://dbad-license.org/)

Die "Don't Be A Dick"-Lizenz erlaubt es dir, das Projekt nach Belieben zu nutzen, mit einer wichtigen Einschränkung:
```
 Sei kein Idiot.
```

### 🎉 Viel Spaß!

Hab Spaß mit diesem kleinen Projekt! Feedback, Verbesserungen und neue Ideen sind immer willkommen. 😄


