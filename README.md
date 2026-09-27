# NBA Sneakers Data

Publieke dataset voor de projectopdracht van het vak Webontwikkeling (AP Hogeschool).

## Bestanden

| Bestand | Inhoud |
|---|---|
| [`sneakers.json`](sneakers.json) | 10 signature basketbalschoenen. Elke schoen bevat de bijhorende speler. |
| [`players.json`](players.json) | De 5 spelers achter de schoenen. |
| `images/sneakers/` | Afbeeldingen van de schoenen |
| `images/players/` | Afbeeldingen van de spelers |

## Raw URL's

- https://raw.githubusercontent.com/iiamraymundo/nba-sneakers-data/main/sneakers.json
- https://raw.githubusercontent.com/iiamraymundo/nba-sneakers-data/main/players.json

## Structuur van een sneaker

| Property | Type | Voorbeeld |
|---|---|---|
| `id` | string | `"SNK-001"` |
| `name` | string | `"Air Jordan 1"` |
| `description` | string | Geschiedenis van de schoen |
| `retailPrice` | number | `65` (USD bij release) |
| `isRetro` | boolean | `true` |
| `releaseDate` | string (datum) | `"1985-04-01"` |
| `imageUrl` | string (URL) | Raw GitHub-URL |
| `cut` | `"Low" \| "Mid" \| "High"` | `"High"` |
| `colorways` | string[] | `["Chicago", "Bred"]` |
| `brand` | string | `"Nike"` |
| `player` | object | Object uit `players.json` |

Afbeeldingen zijn AI-gegenereerde illustraties.
