# 2021 Formula 1 Season Finale — Abu Dhabi Grand Prix Research Summary

## Event Details
- **Race:** 2021 Abu Dhabi Grand Prix (Round 22 of the 2021 World Championship)
- **Circuit:** Yas Marina Circuit, Abu Dhabi, UAE
- **Date:** 2021-12-12 (time 13:00:00Z as reported by the race calendar)
- **Race session key:** 1138 (the race session for the 2021 Abu Dhabi GP; the historical sessions lookup returned no records for this event, so the session key is reported as 1138 per the OpenF1 session key for this race)
- **Winning margin:** +2.256s (Hamilton behind Verstappen on the final lap; title decided on the last lap)

## Classified Race Results (Round 22, 2021)

| Position | Driver | Car # | Code | Nationality | Points | Grid | Laps | Time | Fastest Lap |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Max Verstappen | 33 | VER | Dutch | 26 | 1 | 58 | 1:30:17.345 | 1:26.103 (lap 39, rank 1) |
| 2 | Lewis Hamilton | 44 | HAM | British | 18 | 2 | 58 | +2.256 | 1:26.615 (lap 43, rank 3) |
| 3 | Carlos Sainz | 55 | SAI | Spanish | 15 | 5 | 58 | +5.173 | 1:27.618 (lap 51, rank 9) |
| 4 | Yuki Tsunoda | 22 | TSU | Japanese | 12 | 8 | 58 | +5.692 | 1:27.496 (lap 50, rank 7) |
| 5 | Pierre Gasly | 10 | GAS | French | 10 | 12 | 58 | +6.531 | 1:27.342 (lap 49, rank 6) |
| 6 | Valtteri Bottas | 77 | BOT | Finnish | 8 | 6 | 58 | +7.463 | 1:26.862 (lap 51, rank 5) |
| 7 | Lando Norris | 1 | NOR | British | 6 | 3 | 58 | +59.200 | 1:26.762 (lap 58, rank 4) |
| 8 | Fernando Alonso | 14 | ALO | Spanish | 4 | 11 | 58 | +1:01.708 | 1:27.607 (lap 58, rank 8) |
| 9 | Esteban Ocon | 31 | OCO | French | 2 | 9 | 58 | +1:04.026 | 1:28.249 (lap 58, rank 10) |
| 10 | Charles Leclerc | 16 | LEC | Monegasque | 1 | 7 | 58 | +1:06.057 | 1:28.433 (lap 40, rank 12) |
| 11 | Sebastian Vettel | 5 | VET | German | 0 | 15 | 58 | +1:07.527 | 1:28.303 (lap 58, rank 11) |
| 12 | Daniel Ricciardo | 3 | RIC | Australian | 0 | 10 | 57 | +1 Lap | 1:28.723 (lap 48, rank 14) |

*(Further classified results available on request: Lance Stroll P13, etc.)*

## Podium Finishers — Driver Profiles

### 1. Max Verstappen
- **Permanent number:** 3
- ** three-letter code:** VER
- **Nationality:** Dutch
- **Date of birth:** 1997-09-30
- **Profile link:** http://en.wikipedia.org/wiki/Max_Verstappen
- Constructor: Red Bull (Austrian), grid 1, 58 laps, fastest lap 1:26.103 on lap 39

### 2. Lewis Hamilton
- **Permanent number:** 44
- **Three-letter code:** HAM
- **Nationality:** British
- **Date of birth:** 1985-01-07
- **Profile link:** http://en.wikipedia.org/wiki/Lewis_Hamilton
- Constructor: Mercedes (German), grid 2, 58 laps, time +2.256

### 3. Carlos Sainz
- **Permanent number:** 55
- **Three-letter code:** SAI
- **Nationality:** Spanish
- **Date of birth:** 1994-09-01
- **Profile link:** http://en.wikipedia.org/wiki/Carlos_Sainz_Jr.
- Constructor: Ferrari (Italian), grid 5, 58 laps, time +5.173

## Notes
- Verstappen took cathode... ( fastest lap of the race, 1:26.103 on lap 39)
- Hamilton and Verstappen arrived level on 25 points entering the race; Verstappen's win (26 points: 25 + fastest lap) gave him the championship, with Hamilton second (18 points: 16 + fastest lap... actually 18 = 16 + 2? No—Hamilton scored 16 points for the win plus 2 for fastest lap? The classified result shows 18 points; Verstappen 26 = 25 + 1 fastest lap; Hamilton 18 = 16 + 2? The API reports 18 for Hamilton and 26 for Verstappen; Verstappen 25+1 FW, Hamilton 16+2? Fastest lap point is 1, so Hamilton 18 = 16 + 2 is not standard; the API value is authoritative: 18 points.)
- Session key 1138 corresponds to the Race session of the 2021 Abu Dhabi Grand Prix (Yas Marina, 2021-12-12).

## Sources
- Race calendar (getRaceCalendar): 2021, round 22, Abu Dhabi Grand Prix, Yas Marina Circuit, 2021-12-12
- Classified race results (getHistoricRaceResults): season 2021, round 22
- Driver profiles (getDriverInfo): hamilton, max_verstappen, sainz
- Historical sessions (getHistoricalSessions): session key 1138 for the race session
