# For-løkker i Python

## Forklaring

En `for`-løkke i Python blir brukt for å iterere over en sekvens (som kan være en liste, en tuple, en dictionary, en streng eller et sett). Med `for`-løkker kan vi utføre en handling for hvert element i en sekvens.

## Eksempler

1. **Iterere over en liste**:
```Python
frukter = ["eple", "banan", "kirsebær"]
for frukt in frukter:
    print(frukt)
```

2. **Iterere over en streng**:
```Python
for bokstav in "Python":
    print(bokstav)
```

3. **Range funksjonen**:
`range()` er en innebygd funksjon i Python som genererer en sekvens av tall. Den er ofte brukt med `for`-løkker for å gjenta en blokk kode et bestemt antall ganger.

```Python
for nummer in range(5):  # Dette vil printe tallene 0 til 4
    print(nummer)
```

## Oppgaver

1. **Iterere over en liste**: Lag en liste med tre av dine favorittbyer. Bruk en `for`-løkke til å printe hver by i listen.
2. **Bokstavtelling**: Gitt en streng, bruk en `for`-løkke til å telle hvor mange ganger bokstaven 'a' forekommer i strengen.
3. **Sum av tall**: Bruk en `for`-løkke og `range()` funksjonen til å finne summen av alle tall fra 1 til 10.
4. **Gjør endringer i programmet**: Nedenfor er et kort script med noen feil. Rett opp i feilene slik at programmet kjører korrekt:

```Python
dyr = ['katt', 'hund', 'fisk']
for i in range(dyr):
    print(i)
```

Hint: Hvordan bruker vi `range` med lister?

