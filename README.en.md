[Русский](README.md) | **English**

# Workshop

A cocktail list. A study workshop from 23 August 2023.

## What it does

The screen shows a list of names. On open, the app requests cocktails from `partyshaker.online`.

The project also contains a client for that API: sign-in, ingredients, a bar, favorites, and ratings. Only the cocktail list is connected to the screen.

## Course

A workshop around the PartyShaker API. The network layer was written by Alexandr Rodionov and Anna Shuryaeva. The screen was built by Ilya Shapovalov.

## Stack

SwiftUI, Combine, URLSession.

## Run

```bash
git clone https://github.com/dpogonia/Cocktails-PartyShaker.git
cd Cocktails-PartyShaker
open Workshop23.08.xcodeproj
```

Run the **Workshop23.08** scheme on an iPhone simulator. The list needs access to `partyshaker.online`.

## Author

[Dmitrii Pogonia](https://github.com/dpogonia)
