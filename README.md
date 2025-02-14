# Algemeen
Dit is de GitHub repository van de MIDO/GDI werkgroep toegang. Deze werkgroep is verantwoordelijk voor de (door)ontwikkeling van de domeinarchitectuur toegang. De nieuwe versie van deze architectuur wordt ontwikkeld in de vorm van een ArchiMate architectuurmodel, die te vinden is in deze repository. 

Het architectuurmodel is beschikbaar in verschillende vormen:
1. In de vorm van <a href="toegang.archimate">een bestand</a> voor het modelleertool Archi;
2. Als bestanden die kunnen worden ingelezen met de coArchi plugin van Archi;
3. Als <a href="https://minbzk.github.io/gdi-toegang">website</a> in de vorm van een HTML report uit Archi;
4. In pagina's en overzichten die met een script zijn geëxporteerd uit Archi om er op een vriendelijke manier doorheen te navigeren, inclusief <a href="https://minbzk.github.io/gdi-toegang/content/views/Domeinarchitectuur%20toegang.html">een pagina met een samenvatting van de belangrijkste onderdelen.</a> 

Er zijn <a href="https://github.com/MinBZK/gdi-gegevensuitwisseling/blob/master/instructies.md">instructies</a> beschikbaar voor het aanbrengen van wijzigingen en het installeren en configureren van Archi. Daarnaast is er een beschrijving van het gehanteerde <a href="https://github.com/MinBZK/gdi-gegevensuitwisseling/blob/master/metamodel.md">metamodel</a>. 

Bij de verschillende onderdelen van de architectuur wordt verwezen naar beschrijvingen, diagrammen, overzichten en detailoverzichten. Deze zijn allemaal geëxporteerd uit het architectuurmodelleertool Archi. De diagrammen zijn onderdeel van de standaard Archi HTML report. De overzichten, detailoverzichten en achterliggende detailpagina's zijn gegenereerd met een <a href="scripts/export HTML.ajs">script</a>.

# Architectuur
Inleiding: <a href="https://minbzk.github.io/gdi-toegang/content/elements/id-9704fa59cc7b4b5e9daa53f1b32ec98d.html">beschrijving</a>.

Kernbegrippen: <a href="https://minbzk.github.io/gdi-toegang/content/elements/id-62a0afc676e04f8280ed2271dd61cd44.html">beschrijving</a>.

Veranderfactoren:
* Ontwikkelingen: <a href="https://minbzk.github.io/gdi-toegang/content/views/ontwikkelingen.html">overzicht</a>
* Beleid: <a href="https://minbzk.github.io/gdi-toegang/content/views/beleid.html">overzicht</a>
* Wet- en regelgeving: <a href="https://minbzk.github.io/gdi-toegang/content/views/wetten.html">overzicht</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/wettendetails.html">details</a>
* Knelpunten: <a href="https://minbzk.github.io/gdi-toegang/content/views/knelpunten.html">overzicht</a>
* Capabilities: <a href="https://minbzk.github.io/gdi-toegang/?view=id-0b1de22ff1b248798b095a178cf065f8">diagram</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/capabilities.html">overzicht</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/capabilitiesdetails.html">details</a>

Gewenste situatie:
* Architectuurvisie: <a href="https://minbzk.github.io/gdi-toegang/content/elements/id-57896b8c4e854e7b92ed667986aa09ee.html">beschrijving</a>
* Architectuurprincipes: <a href="https://minbzk.github.io/gdi-toegang/?view=id-4e701366fd844120b700c114068bc91e">diagram</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/principes.html">overzicht</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/principesdetails.html">details</a>
* Verdieping op thema rolverdeling: <a href="https://minbzk.github.io/gdi-toegang/content/elements/id-df84c34285474bdebefd163a965d6403.html">beschrijving</a>
* Verdieping op thema systeem naar systeem toegang: <a href="https://minbzk.github.io/gdi-toegang/content/elements/id-7af4783895fc4fb6b4cb8e96e8708e85.html">beschrijving</a>
* Veranderinitiatieven: <a href="https://minbzk.github.io/gdi-toegang/content/views/veranderinitiatieven.html">overzicht</a>

Bijlagen:
* Functies: <a href="https://minbzk.github.io/gdi-toegang/?view=id-e1cf58e0b07f4907bdce34ba561b9a18">diagram</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/bedrijfsfuncties.html">overzicht</a>
* Bedrijfsobjecten: <a href="https://minbzk.github.io/gdi-toegang/?view=id-efc531031d114860a309f6eeacdad289">diagram</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/bedrijfsobjecten.html">overzicht</a>
* Relatie tussen functies en bedrijfsobjecten: <a href="https://minbzk.github.io/gdi-toegang/?view=id-d24214a9135947e980983cea632143d2">diagram</a>
* Rollen: <a href="https://minbzk.github.io/gdi-toegang/content/views/rollen.html">overzicht</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/rollendetails.html">details</a>
* Huidige voorzieningen: <a href="https://minbzk.github.io/gdi-toegang/?view=id-6b127e72ba554982a8ade48d06e2286c">diagram</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/huidige%20voorzieningen.html">overzicht</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/huidige%20voorzieningendetails.html">details</a>
* Standaarden: <a href="https://minbzk.github.io/gdi-toegang/?view=id-f14d78e817cf494cabe940d8c59f8a4e">diagram</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/standaarden.html">overzicht</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/standaardendetails.html">details</a>
* Begrippen: <a href="https://minbzk.github.io/gdi-toegang/content/views/begrippen.html">overzicht</a>, <a href="https://minbzk.github.io/gdi-toegang/content/views/begrippendetails.html">details</a>
* Relatie van architectuurprincipes met ADO en NORA: <a href="https://minbzk.github.io/gdi-toegang/content/elements/id-2ce199487e094f099863995e07a7e605.html">overzicht</a>
* Betrokkenen: <a href="https://minbzk.github.io/gdi-toegang/content/elements/id-db058829d6194cd59fd9d78182fb6933.html">beschrijving</a>

Documenten:
* Samenvatting van de belangrijkste onderdelen in één pagina: <a href="https://minbzk.github.io/gdi-toegang/content/views/Domeinarchitectuur%20toegang.html">samenvatting</a>