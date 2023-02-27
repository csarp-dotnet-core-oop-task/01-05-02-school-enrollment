# 01-05-02-school-enrollment
Iskolai felvételi

Teszt kód
```
PointSummary josephTakenScore=new PointSummary(83,94);
Console.WriteLine(josephTakenScore);
PointSummary johephAdmissionScore = new PointSummary(74, 85);
Console.WriteLine(johephAdmissionScore);

SchoolEnrollmentScore josephEnrollment = new SchoolEnrollmentScore("József", josephTakenScore, johephAdmissionScore);
Console.WriteLine(josephEnrollment);

PointSummary elisabethTakenScore = new PointSummary(87, 93);   
PointSummary elisabethAdmissionScore = new PointSummary(77, 89);
SchoolEnrollmentScore elisabethEnrollment = new SchoolEnrollmentScore("Erzsébet", elisabethTakenScore, elisabethAdmissionScore);
Console.WriteLine(elisabethEnrollment);

if (elisabethEnrollment.TotalScore> josephEnrollment.TotalScore)
Console.WriteLine("Erzsébetnek több felvételi pontja van mint Józsefnek.");
else if (elisabethEnrollment.TotalScore < josephEnrollment.TotalScore)
Console.WriteLine("Erzsébetnek kevesebb felvételi pontja van mint Józsefnek.");
else
Console.WriteLine("Erzsébetnek ugyan annyi felvételi pontja van mint Józsefnek.");
```
Futási eredmény
```
Matematika pontszám: 83 pont.
Anyanyelv pontszám: 94 pont.
Összpontszám: 177 pont.
Átlag pontszám: 88,5 pont.
Matematika pontszám: 74 pont.
Anyanyelv pontszám: 85 pont.
Összpontszám: 159 pont.
Átlag pontszám: 79,5 pont.

A felvételiző neve:József
József hozott pontszáma:
Matematika pontszám: 83 pont.
Anyanyelv pontszám: 94 pont.
Összpontszám: 177 pont.
Átlag pontszám: 88,5 pont.
József felvételin elért pontszáma:
Matematika pontszám: 74 pont.
Anyanyelv pontszám: 85 pont.
Összpontszám: 159 pont.
Átlag pontszám: 79,5 pont.
József felvételi összpontszáma:168



A felvételiző neve:Erzsébet
Erzsébet hozott pontszáma:
Matematika pontszám: 87 pont.
Anyanyelv pontszám: 93 pont.
Összpontszám: 180 pont.
Átlag pontszám: 90 pont.
Erzsébet felvételin elért pontszáma:
Matematika pontszám: 77 pont.
Anyanyelv pontszám: 89 pont.
Összpontszám: 166 pont.
Átlag pontszám: 83 pont.
Erzsébet felvételi összpontszáma:173

Erzsébetnek több felvételi pontja van mint Józsefnek.
```
