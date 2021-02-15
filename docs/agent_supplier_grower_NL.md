# Agent/Supplier/Grower

VMP4ALL ziet zich zelf niet als een partij in het berichtenverkeer.


## Rollen

### Kweker (SupplyTradeLineItem\Product\ManufacturerParty)
De kweker van het product

### Leverancier (SupplyTradeLineItem\SupplierParty)
Veel branch software koppelt een VMP koppeling aan een vaste leverancier. Met VMP4ALL kan iedereen een eigen koppeling aanmaken met hierin een zelf gefiltert aanbod van diversen leveranciers en kwekers.
Dit kan in de ERP software van de exporteur (buyer) soms wat hinder geven bij het binnenmelden. Dit omdat er in de ERP software niet direct te zien is wie de leverancier is van een binnenkomende partij.
VMP4ALL raad aan om in de software het leverancier veld uit een VMP order op te slaan bij een partij, zodat dit voorkomen kan worden.

### Agent (AgentParty)
VMP4ALL zal zichzelf als agent mee geven in de berichten.
