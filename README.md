Lunar Flowchart Control
Denne opgave gik ud på at omsætte et flowchart til et fungerende C-program, der styrer en rumfærges thruster ud fra dens højde (altitude).
Formålet var at lære at oversætte logiske beslutningsstrukturer fra et diagram til faktiske if-else betingelser i C.
Programmet indeholder en funktion Control(int altitude), som bestemmer om thruster skal være tændt eller slukket:

Hvis altitude > 100 → thruster off (thruster = 0)

Hvis 0 < altitude ≤ 100 → thruster on (thruster = 1)

Hvis altitude ≤ 0 → thruster off (thruster = 0)

Derudover testes funktionen med flere højder i funktionen Test(), som sammenligner thrusterens output med den forventede adfærd og udskriver “OK” eller “FAIL”.
Eksempel på korrekt output:
For altitude 150, your thruster is 0 | OK |
For altitude 100, your thruster is 1 | OK |
For altitude  50, your thruster is 1 | OK |
For altitude   0, your thruster is 0 | OK |
For altitude  -1, your thruster is 0 | OK |

Opgaven viser forståelsen af betinget logik, funktioner, og hvordan man systematisk kan teste programadfærd ud fra et flowchart.
