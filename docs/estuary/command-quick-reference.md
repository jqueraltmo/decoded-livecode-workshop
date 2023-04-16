![DECODED Banner](images/banner_estuary.png)

# Referència ràpida d'ordres

![Estuary Terminal](images/estuary_terminal.png)

## Modificadors de la vista

*Veure quines vistes hi ha disponibles*
```
!listviews
```

---

*Triar una vista per mostrar localment (només al teu ordinador) de la sortida anterior.*
```
!presetview n
```

---

*Assignar la vista actual a tots els usuaris de la banda.*
```
!publishview def
```

---

 *Tornar a la vista per defecte a la teva finestra.*
```
!presetview def
```

---

*Veure quin codi genera la vista actual.*
```
!dumpview
```

---

*Llistar totes les mostres.*
```
!localview audiomap
```

---

*Mostrar només els visuals, a la finestra local.*
```
!localview []
```

---

*Mostrar `iframes` en cel·les, veure vdo.ninja*
```
!localview $ grid 2 2 [iFrame "https://en.wikipedia.org/wiki/4hero",code 0 0,code 1 0,iFrame "https://en.wikipedia.org/wiki/4hero"]
```

---

## Funcions útils

*Veure el tempo*
```
!showtempo
```

---

*Assignar el tempo, en cicles per segon. Entre 0 i 1 són valors segurs.*
```
!setcps x.y
```

---

*[afegir mostres del teu servidor](https://github.com/dktr0/estuary/wiki#adding-sound-files-to-estuarywebdirt-on-the-fly-early-august-2021)*

```
!reslist "https://el.teu.domini/resources.json"
```

---

*Veure quins recursos externs s'han carregat.*
```
!showresources
```

---

 *Tornar als recursos per defecte proporcionats per Estuary.*
```
!defaultresources
```

---

 *Eliminar tots els recursos, inclosos els proporcionats per defecte.*
```
!clearresources
```

**[Copyright](/COPYRIGHT.md)**
