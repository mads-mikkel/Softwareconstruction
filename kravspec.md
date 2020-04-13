# KRAVSPECIFIKATION
### FUNKTIONELLE KRAV
* Lagermedarbejderen skal kunne se en oversigt over de produkter der er 5 eller færre af.
* Lagermedarbejderen skal kunne angive at en vare er i restordre (udgået: antal = 0).
* Lagermedarbejderen skal kunne se førernavn, ankomsttid, logistik leverandærm, hænger nummerplade og hænger land for dagens ankomne transporter til lageret.
* Controlleren skal skal kunne bestille produkter hos leverandører.
* Kunder skal kunne afgive ordrer.
* Kunder skal kunne se ordrestatus på afgivne ordrer.

### IKKE-FUNKTIONELLE KRAV
* Alle applikationer udvikles i C# og afvikles på .NET Core 3.1 runtime på den relevante enhed.
* Lagermedarbejderen skal tilgå systemet via Windows 10 PC med en applikation udviklet i WPF.
* Controllere skal tilgå systemet via Windows 10 PC med applikation udviklet i UWP.
* Kunder skal tilgå systemet via web site udviklet i ASP.NET Core, når kunden skal afgive ordre.
* Kudner skal tilgå systemet via mobil app udviklet i Xamarin, når kunden skal se ordrestatus.
