# EU shop duties: reference list

Data as of: 2026-11-25

Every date and requirement was checked against the listed sources on that day. The list covers EU-wide rules and, for EU directives, the German implementation.

## How to read the conditions

Conditions use `&` (and), `|` (or), `!` (not) and brackets. The names mean:

- `sells_de`: sells to customers in Germany
- `sells_eu_other`: sells to customers in other EU countries
- `sells_eu`: true when `sells_de` or `sells_eu_other` is true
- `seat=de`, `seat=eu`, `seat=non_eu`: company is based in Germany, in another EU country, outside the EU
- `b2c`: sells to consumers
- `b2b`: sells to businesses
- `own_import`: sells under an own brand or imports goods from outside the EU directly
- `micro`: fewer than 10 staff and at most EUR 2 million annual turnover
- `ai`: uses an AI chatbot for customers or publishes deceptively realistic AI images, video or audio
- `green_claims`: advertises with environmental claims or own eco labels
- `physical`: sells at least one kind of physical goods
- `has:textiles`: sells clothing, textiles, shoes
- `has:electronics`: sells electrical and electronic devices
- `has:batteries`: sells batteries, e-bikes, e-scooters
- `has:furniture_wood`: sells furniture, wood and paper goods
- `has:agri`: sells coffee, cocoa, leather, rubber, soy, palm oil (also processed)
- `has:other_physical`: sells other physical goods
- `has:digital`: sells digital products, subscriptions, services

## Duties

### 1. Product safety: mandatory details in each listing (GPSR)

- Id: `gpsr`
- Applies when: `sells_eu & physical`
- Date: 2024-12-13
- Scope: EU regulation, same across the EU
- Legal basis: Art. 19 Verordnung (EU) 2023/988 (GPSR)
- Summary: Applies to consumer products. Every online listing must show who is responsible for the product.
- What to do:
  - Show clearly in the listing: name, postal address and electronic address of the manufacturer.
  - Show details that identify the product (for example image and type) plus warnings and safety information.
  - If you sell products under your own brand, you count as the manufacturer.
- Extra, only when `own_import | seat=non_eu`: If the manufacturer is based outside the EU, the listing must also show the name, address and electronic address of a responsible person in the EU.
- Sources: [IHK Chemnitz – Produktsicherheitsverordnung](https://www.ihk.de/chemnitz/innovation/innovation-technologie/verordnung-produktsicherheit-6310542), [Händlerbund – GPSR](https://www.haendlerbund.de/de/ratgeber/recht/produktsicherheitsverordnung)
- German wording:
  - Titel: Produktsicherheit: Pflichtangaben im Angebot (GPSR)
  - Kurz: Gilt für Verbraucherprodukte. Jedes Online-Angebot muss zeigen, wer für das Produkt verantwortlich ist.
  - Zu tun: Im Angebot gut sichtbar angeben: Name, Postanschrift und elektronische Adresse des Herstellers.
  - Zu tun: Angaben zur Identifizierung des Produkts (zum Beispiel Bild und Typ) sowie Warn- und Sicherheitshinweise zeigen.
  - Zu tun: Wer Produkte unter eigener Marke verkauft, gilt selbst als Hersteller.
  - Zusatz, nur wenn `own_import | seat=non_eu`: Sitzt der Hersteller außerhalb der EU, müssen zusätzlich Name, Anschrift und elektronische Adresse einer verantwortlichen Person in der EU im Angebot stehen.

### 2. Discount advertising: lowest price of the last 30 days

- Id: `price_reduction`
- Applies when: `sells_eu & b2c & physical`
- Date: 2022-05-28
- Scope: EU directive, implemented per country (German law shown)
- Legal basis: § 11 PAngV; Richtlinie (EU) 2019/2161
- Summary: Only relevant if you advertise price reductions, for example strike-through prices or percentages.
- What to do:
  - For every price reduction on goods, state the lowest total price you charged in the 30 days before it.
  - Base the strike-through price and any percentage on that 30-day lowest price.
- Sources: [IT-Recht Kanzlei – Preisermäßigungen (§ 11 PAngV)](https://www.it-recht-kanzlei.de/faq-werbung-preisermaessigungen-gesamtpreis-preisangabenverordnung.html), [§ 11 PAngV (Gesetzestext)](https://www.gesetze-im-internet.de/pangv_2022/__11.html)
- German wording:
  - Titel: Rabattwerbung: niedrigster Preis der letzten 30 Tage
  - Kurz: Nur relevant, wenn Sie mit Preisermäßigungen werben, etwa mit Streichpreisen oder Prozenten.
  - Zu tun: Bei jeder Preisermäßigung für Waren den niedrigsten Gesamtpreis angeben, den Sie in den 30 Tagen davor verlangt haben.
  - Zu tun: Streichpreis und Prozentangabe auf diesen 30-Tage-Tiefstpreis beziehen.

### 3. Accessible online shop

- Id: `accessibility`
- Applies when: `sells_eu & b2c & !micro`
- Date: 2025-06-28
- Scope: EU directive, implemented per country (German law shown)
- Legal basis: Barrierefreiheitsstärkungsgesetz (BFSG); Richtlinie (EU) 2019/882
- Summary: Online shops for consumers must also be usable by people with disabilities.
- What to do:
  - Make the shop accessible: keyboard operation, sufficient contrast, alternative text for images, understandable forms. In practice the WCAG guidelines are used as the benchmark.
  - Describe how the shop meets the requirements (for example in the terms and conditions or an accessibility statement).
- Not applicable when `sells_eu & b2c & micro`: Micro-enterprises (fewer than 10 staff and at most EUR 2 million turnover or balance sheet total) are exempt for the online shop itself. If you sell devices the law names explicitly (for example computers, smartphones, e-readers), those products must still be accessible.
- Sources: [IHK Gera – Barrierefreiheit im Onlinehandel](https://www.ihk.de/gera/recht-und-steuern/fokus-onlinehandel/barrierefreiheit-im-onlinehandel-6545152), [IHK München – Barrierefreiheitsstärkungsgesetz](https://www.ihk-muenchen.de/ratgeber/recht/werbung-fairer-wettbewerb/barrierefreiheitsstaerkungsgesetz/)
- German wording:
  - Titel: Barrierefreier Onlineshop
  - Kurz: Onlineshops für Verbraucher müssen auch für Menschen mit Behinderungen nutzbar sein.
  - Zu tun: Den Shop barrierefrei gestalten: Bedienung mit der Tastatur, ausreichende Kontraste, Alternativtexte für Bilder, verständliche Formulare. In der Praxis gelten die WCAG-Richtlinien als Maßstab.
  - Zu tun: Beschreiben, wie der Shop die Anforderungen erfüllt (zum Beispiel in den AGB oder einer Erklärung zur Barrierefreiheit).
  - Nicht betroffen, wenn `sells_eu & b2c & micro`: Kleinstunternehmen (weniger als 10 Beschäftigte und höchstens 2 Millionen Euro Umsatz oder Bilanzsumme) sind für den Onlineshop selbst ausgenommen. Verkaufen Sie Geräte, die das Gesetz ausdrücklich nennt (zum Beispiel Computer, Smartphones, E-Book-Reader), müssen diese Produkte trotzdem barrierefrei sein.

### 4. Withdrawal button (online withdrawal function)

- Id: `withdrawal_button`
- Applies when: `sells_eu & b2c`
- Date: 2026-06-19
- Scope: EU directive, implemented per country (German law shown)
- Legal basis: § 356a BGB; Richtlinie (EU) 2023/2673
- Summary: Consumers must be able to withdraw from contracts concluded online through a clearly visible button. This does not apply where no right of withdrawal exists.
- What to do:
  - Offer the withdrawal function throughout the whole withdrawal period, easy to read and easy to reach, without requiring a login.
  - Use two steps: enter the details, then send them with a confirmation button.
  - Confirm receipt immediately on a durable medium (for example by email), with date and time.
  - Add a note about the function to your withdrawal policy.
- Sources: [IHK Rheinhessen – Widerrufsbutton](https://www.ihk.de/rheinhessen/rechtundsteuern/gesetzesaenderung/widerrufsbutton-7034868), [WKO – FAQ Widerrufsbutton](https://www.wko.at/handeldigital/faq-widerrufsbutton-webshop)
- German wording:
  - Titel: Widerrufsbutton (elektronische Widerrufsfunktion)
  - Kurz: Verbraucher müssen online geschlossene Verträge über eine gut sichtbare Schaltfläche widerrufen können. Das gilt nicht, wo kein Widerrufsrecht besteht.
  - Zu tun: Die Widerrufsfunktion während der gesamten Widerrufsfrist gut lesbar und leicht zugänglich anbieten, ohne Login als Voraussetzung.
  - Zu tun: Zwei Schritte vorsehen: Angaben eingeben, dann über eine Bestätigungs-Schaltfläche absenden.
  - Zu tun: Den Eingang sofort auf einem dauerhaften Datenträger bestätigen (zum Beispiel per E-Mail), mit Datum und Uhrzeit.
  - Zu tun: Die Widerrufsbelehrung um den Hinweis auf die Funktion ergänzen.

### 5. Right to repair: new rules for defects

- Id: `repair`
- Applies when: `sells_eu & b2c & physical`
- Date: 2026-07-31
- Scope: EU directive, implemented per country (German law shown)
- Legal basis: § 475 BGB n. F.; Richtlinie (EU) 2024/1799
- Summary: Applies to sales contracts with consumers concluded from 31 July 2026.
- What to do:
  - When a customer reports a defect, inform them that they can choose between repair and replacement, and that the legal guarantee is extended once by twelve months if they choose repair.
  - Update terms and conditions, complaint handling and text templates for the possible extension.
- Extra, only when `own_import & has:electronics`: For certain devices (for example washing machines, fridges, smartphones) the manufacturer has a duty to repair. If the manufacturer is outside the EU, that duty can pass to the authorised representative, the importer or finally the distributor.
- Sources: [IHK München – Recht auf Reparatur](https://www.ihk-muenchen.de/ratgeber/recht/vertragsrecht/recht-auf-reparatur/), [IT-Recht Kanzlei – Recht auf Reparatur](https://www.it-recht-kanzlei.de/recht-auf-reparatur-2026.html)
- German wording:
  - Titel: Recht auf Reparatur: neue Regeln bei Mängeln
  - Kurz: Gilt für Kaufverträge mit Verbrauchern ab dem 31. Juli 2026.
  - Zu tun: Im Gewährleistungsfall über das Wahlrecht zwischen Reparatur und Ersatzlieferung informieren und darüber, dass sich die Gewährleistung bei einer Reparatur einmalig um zwölf Monate verlängert.
  - Zu tun: AGB, Reklamationsabläufe und Textbausteine an die mögliche Verlängerung anpassen.
  - Zusatz, nur wenn `own_import & has:electronics`: Für bestimmte Geräte (zum Beispiel Waschmaschinen, Kühlschränke, Smartphones) hat der Hersteller eine Reparaturpflicht. Sitzt er außerhalb der EU, kann sie auf den Bevollmächtigten, den Importeur oder zuletzt den Händler übergehen.

### 6. Disclose AI: chatbots and deceptively realistic AI content

- Id: `ai_transparency`
- Applies when: `sells_eu & ai`
- Date: 2026-08-02
- Scope: EU regulation, same across the EU
- Legal basis: Art. 50 Verordnung (EU) 2024/1689 (KI-Verordnung)
- Summary: There is no general duty to label every AI text or AI image.
- What to do:
  - Tell customers explicitly when they are writing or talking to an AI system instead of a person.
  - Label deceptively realistic AI images, video or audio (deepfakes) as artificially generated.
- Sources: [IHK Schleswig-Holstein – KI-Kennzeichnung](https://www.ihk.de/sh/ki-kennzeichnung), [IHK Frankfurt – Transparenzpflichten bei KI](https://www.frankfurt-main.ihk.de/recht/uebersicht-alle-rechtsthemen/digitalisierung2/transparenzpflichten-beim-einsatz-von-ki-systemen-7126880)
- German wording:
  - Titel: KI offenlegen: Chatbots und täuschend echte KI-Inhalte
  - Kurz: Eine allgemeine Kennzeichnungspflicht für jeden KI-Text oder jedes KI-Bild gibt es nicht.
  - Zu tun: Kunden ausdrücklich darauf hinweisen, wenn sie mit einem KI-System statt mit einem Menschen schreiben oder sprechen.
  - Zu tun: Täuschend echte KI-Bilder, -Videos oder -Tonaufnahmen (Deepfakes) als künstlich erzeugt kennzeichnen.

### 7. Packaging: EU Packaging Regulation (PPWR)

- Id: `packaging`
- Applies when: `sells_eu & physical`
- Date: 2026-08-12
- Scope: EU regulation, same across the EU
- Legal basis: Verordnung (EU) 2025/40 (PPWR)
- Summary: Applies to everyone who ships packaged goods to customers in the EU. Further stages follow in the coming years.
- What to do:
  - For each EU country you ship to end customers directly, clarify whether you must register there and join a take-back scheme (in Germany: the LUCID register).
  - Make sure your packaging carries the mandatory identification and producer details. The packaging producer is responsible. For packaging under your own name that can be you.
  - Collect material type and weight of your packaging and evidence from suppliers.
  - The harmonised EU label comes on 12 August 2028 at the earliest.
- Extra, only when `seat=non_eu | sells_eu_other`: Without an establishment in the destination country you may need an authorised representative there.
- Sources: [Zentrale Stelle Verpackungsregister – Onlinehandel und PPWR](https://www.verpackungsregister.org/information-orientierung/hilfe-erklaerung/faq-index/detail/413-was-gilt-fuer-den-online-handel), [Händlerbund – PPWR-Kennzeichnung](https://www.haendlerbund.de/de/news/aktuelles/wissenssnack/ppwr-kennzeichnungspflicht), [WKO – FAQ Verpackungsverordnung](https://www.wko.at/handel/versandhandel/faq-verpackungsverordnung)
- German wording:
  - Titel: Verpackungen: EU-Verpackungsverordnung (PPWR)
  - Kurz: Gilt für alle, die verpackte Ware an Kunden in der EU schicken. Weitere Stufen folgen in den nächsten Jahren.
  - Zu tun: Für jedes EU-Land, in das Sie direkt an Endkunden liefern, klären, ob Sie sich dort registrieren und an einem Rücknahmesystem beteiligen müssen (in Deutschland: Register LUCID).
  - Zu tun: Darauf achten, dass Ihre Verpackungen die Pflichtangaben zur Identifikation und zum Erzeuger tragen. Zuständig ist der Erzeuger der Verpackung. Bei Verpackungen unter Ihrem eigenen Namen können das Sie sein.
  - Zu tun: Materialart und Gewicht Ihrer Verpackungen sowie Nachweise der Lieferanten sammeln.
  - Zu tun: Das einheitliche EU-Label kommt frühestens am 12. August 2028.
  - Zusatz, nur wenn `seat=non_eu | sells_eu_other`: Ohne Niederlassung im Zielland kann dort ein Bevollmächtigter nötig sein.

### 8. EU labels for legal guarantee and commercial guarantee

- Id: `warranty_label`
- Applies when: `sells_eu & b2c & physical`
- Date: 2026-09-27
- Scope: EU directive, implemented per country (German law shown)
- Legal basis: Art. 246 EGBGB; Richtlinie (EU) 2024/825; Durchführungsverordnung (EU) 2025/1960
- Summary: The legal guarantee itself does not change. What is new is the duty to show it prominently with a uniform EU label.
- What to do:
  - Show the 'harmonised notice' on the legal guarantee clearly before purchase, in colour in the online shop.
  - If the manufacturer offers a commercial guarantee of durability, the EU guarantee label (GARAN) can be mandatory as well. The exact conditions are in the source.
  - Use only the official EU templates.
- Sources: [IHK München – Labels für Gewährleistung und Garantie](https://www.ihk-muenchen.de/ratgeber/recht/vertragsrecht/labels-fuer-gewaehrleistung-und-garantie/), [IHK Nord Westfalen – Gewährleistung und Garantie](https://www.ihk.de/nordwestfalen/recht/aktuelles/garantien-und-gewaehrleistung-neue-informationspflichten2-7096724)
- German wording:
  - Titel: EU-Label für Gewährleistung und Garantie
  - Kurz: Am Gewährleistungsrecht selbst ändert sich nichts. Neu ist die Pflicht, es mit einem einheitlichen EU-Label hervorgehoben zu zeigen.
  - Zu tun: Die «harmonisierte Mitteilung» zum gesetzlichen Gewährleistungsrecht vor dem Kauf gut sichtbar zeigen, im Onlineshop in Farbe.
  - Zu tun: Gibt der Hersteller eine gewerbliche Haltbarkeitsgarantie, kann zusätzlich das EU-Garantielabel (GARAN) Pflicht sein. Die genauen Voraussetzungen stehen in der Quelle.
  - Zu tun: Nur die offiziellen Vorlagen der EU verwenden.

### 9. Advertising with environmental claims

- Id: `green_claims`
- Applies when: `sells_eu & b2c & green_claims`
- Date: 2026-09-27
- Scope: EU directive, implemented per country (German law shown)
- Legal basis: UWG (Anhang zu § 3 Abs. 3); Richtlinie (EU) 2024/825
- Summary: Much stricter rules apply to environmental and sustainability claims made to consumers.
- What to do:
  - Use general claims such as 'eco-friendly', 'green' or 'sustainable' only if you can prove the environmental performance and explain the claim specifically.
  - Do not use your own sustainability labels without a certification scheme.
  - Do not claim that a product is climate neutral or better for the climate if that rests on offsetting greenhouse gas emissions.
  - Review website, product texts, packaging and ads.
- Sources: [IHK Köln – Green Claims](https://www.ihk.de/koeln/hauptnavigation/ihkplus/ihkplus-2026-3-green-claims-7216856), [IHK Fulda – EmpCo gegen Greenwashing](https://www.ihk.de/fulda/innovation/umweltschutz/nachhaltigkeit/empco-green-claims-7169030)
- German wording:
  - Titel: Werbung mit Umweltaussagen
  - Kurz: Für Umwelt- und Nachhaltigkeitsaussagen gegenüber Verbrauchern gelten deutlich strengere Regeln.
  - Zu tun: Allgemeine Aussagen wie «umweltfreundlich», «grün» oder «nachhaltig» nur verwenden, wenn Sie die Umweltleistung belegen können und die Aussage konkret erläutern.
  - Zu tun: Keine eigenen Nachhaltigkeitssiegel ohne Zertifizierungssystem verwenden.
  - Zu tun: Nicht behaupten, ein Produkt sei klimaneutral oder klimafreundlicher, wenn das auf dem Ausgleich (Kompensation) von Treibhausgasen beruht.
  - Zu tun: Website, Produkttexte, Verpackung und Anzeigen durchsehen.

### 10. New product liability for importers and own brands

- Id: `product_liability`
- Applies when: `sells_eu & physical & own_import`
- Date: 2026-12-09
- Scope: EU directive, implemented per country (German law shown)
- Legal basis: Produkthaftungsgesetz (neu); Richtlinie (EU) 2024/2853
- Summary: Applies to products placed on the market from 9 December 2026. If you import goods from outside the EU, you can be liable for product defects yourself.
- What to do:
  - Clarify your role: manufacturer, importer or distributor.
  - Review product liability insurance and supplier contracts.
  - Keep technical documentation and supplier evidence in good order.
- Sources: [IHK Nord Westfalen – Produkthaftung 2026](https://www.ihk.de/nordwestfalen/recht/aktuelles/neue-regelungen-zur-produkthaftung-2026-7236026), [IHK Köln – Neues Produkthaftungsrecht](https://www.ihk.de/koeln/hauptnavigation/recht-steuern/neues-produkthaftungsrecht-ab-dezember-2026-7219976)
- German wording:
  - Titel: Neue Produkthaftung für Importeure und Eigenmarken
  - Kurz: Gilt für Produkte, die ab dem 9. Dezember 2026 in Verkehr gebracht werden. Wer Ware von außerhalb der EU einführt, kann selbst für Produktfehler haften.
  - Zu tun: Klären, welche Rolle Sie haben: Hersteller, Importeur oder Händler.
  - Zu tun: Produkthaftpflicht-Versicherung und Lieferantenverträge prüfen.
  - Zu tun: Technische Unterlagen und Nachweise der Lieferanten geordnet aufbewahren.

### 11. Deforestation-free supply chains (EUDR)

- Id: `eudr`
- Applies when: `sells_eu & (has:furniture_wood | has:agri)`
- Date: 2026-12-30
- Date if `micro & !has:furniture_wood`: 2027-06-30
- Scope: EU regulation, same across the EU
- Legal basis: Verordnung (EU) 2023/1115, geändert durch (EU) 2025/2650
- Summary: Covers wood, rubber, cattle (leather), coffee, cocoa, palm oil, soy and goods made from them. Start: 30 December 2026 for medium and large companies, 30 June 2027 for small and micro companies. For wood goods that already fell under the EU Timber Regulation, 30 December 2026 also applies to small companies.
- What to do:
  - Use the customs codes to check whether your products are listed in the annex of the regulation.
- Extra, only when `own_import`: If you import affected goods into the EU yourself, you are the first to place them on the market: check the origin and submit a due diligence statement in the EU information system before selling.
- Extra, only when `!own_import`: If you buy within the EU, you do not submit your own due diligence statement. Ask your supplier for the reference number of their statement and keep it.
- Sources: [IHK Rhein-Neckar – EUDR](https://www.ihk.de/rhein-neckar/international/export-import/einfuhr/eudr-wie-sie-sich-optimal-vorbereiten-6694256), [EU-Kommission (Access2Markets) – EUDR](https://trade.ec.europa.eu/access-to-markets/de/news/verzoegerung-bis-dezember-2026-und-weitere-entwicklungen-bei-der-umsetzung-der-eudr-verordnung)
- German wording:
  - Titel: Entwaldungsfreie Lieferketten (EUDR)
  - Kurz: Betrifft Holz, Kautschuk, Rinder (Leder), Kaffee, Kakao, Palmöl, Soja und daraus hergestellte Waren. Start: 30. Dezember 2026 für mittlere und große Unternehmen, 30. Juni 2027 für kleine und Kleinstunternehmen. Für Holzwaren, die schon unter die EU-Holzhandelsverordnung fielen, gilt der 30. Dezember 2026 auch für kleine Unternehmen.
  - Zu tun: Anhand der Warennummern prüfen, ob Ihre Produkte im Anhang der Verordnung stehen.
  - Zusatz, nur wenn `own_import`: Wer betroffene Ware selbst in die EU einführt, bringt sie als Erster in Verkehr: Herkunft prüfen und vor dem Verkauf eine Sorgfaltserklärung im EU-Informationssystem abgeben.
  - Zusatz, nur wenn `!own_import`: Wer in der EU einkauft, gibt keine eigene Sorgfaltserklärung ab. Lassen Sie sich vom Lieferanten die Referenznummer seiner Erklärung geben und bewahren Sie sie auf.

### 12. E-invoices to business customers in Germany

- Id: `einvoice_de`
- Applies when: `seat=de & b2b & sells_de`
- Date: 2027-01-01
- Scope: Germany only
- Legal basis: § 14 UStG
- Summary: Only concerns invoices to other businesses within Germany. Invoices to consumers are not affected.
- What to do:
  - Be able to receive e-invoices. This has applied since 1 January 2025.
  - From 1 January 2027, issue e-invoices yourself if your total turnover in 2026 was above EUR 800,000.
  - From 1 January 2028 the duty applies to everyone. Small businesses under § 19 UStG do not have to issue e-invoices but must be able to receive them.
- Not applicable when `!seat=de & b2b & sells_de`: The German e-invoicing duty only applies to businesses established in Germany. Other countries have their own rules.
- Sources: [IHK Stuttgart – E-Rechnung](https://www.ihk.de/stuttgart/fuer-unternehmen/recht-und-steuern/steuerrecht/steuermeldungen/e-rechnungen-5864496), [IHK Rhein-Neckar – E-Rechnungspflicht](https://www.ihk.de/rhein-neckar/recht/steuerrecht/umsatzsteuer/e-rechnungspflicht-5931752)
- German wording:
  - Titel: E-Rechnung an Geschäftskunden in Deutschland
  - Kurz: Betrifft nur Rechnungen an andere Unternehmen im Inland. Rechnungen an Verbraucher sind nicht betroffen.
  - Zu tun: E-Rechnungen empfangen können. Das gilt bereits seit dem 1. Januar 2025.
  - Zu tun: Ab 1. Januar 2027 selbst E-Rechnungen ausstellen, wenn Ihr Gesamtumsatz 2026 über 800.000 Euro lag.
  - Zu tun: Ab 1. Januar 2028 gilt die Pflicht für alle. Kleinunternehmer nach § 19 UStG müssen keine E-Rechnungen ausstellen, aber empfangen können.
  - Nicht betroffen, wenn `!seat=de & b2b & sells_de`: Die deutsche Pflicht zur E-Rechnung gilt nur für Unternehmen, die in Deutschland ansässig sind. Andere Länder haben eigene Regeln.

### 13. Batteries: battery passport and replaceable batteries

- Id: `battery`
- Applies when: `sells_eu & (has:batteries | has:electronics)`
- Date: 2027-02-18
- Scope: EU regulation, same across the EU
- Legal basis: Verordnung (EU) 2023/1542 (Batterieverordnung)
- Summary: The battery passport is the first binding digital product passport in the EU.
- What to do:
  - Batteries for e-bikes and e-scooters, electric vehicle batteries and industrial batteries above 2 kWh need a digital battery passport with a QR code from 18 February 2027.
  - Manufacturers and importers must provide it. As a distributor, have your supplier confirm that the passport exists.
  - For devices with built-in batteries, rules on removability and replaceability of the batteries apply from the same day.
- Sources: [IHK Bodensee-Oberschwaben – Digitaler Produktpass](https://www.ihk.de/bodensee-oberschwaben/innovation/innovation-und-technologie/produktentwicklung/der-digitale-produktpass-6801576), [Händlerbund – Gesetzesänderungen 2027](https://www.haendlerbund.de/de/ratgeber/recht/gesetzesaenderungen-2027)
- German wording:
  - Titel: Batterien: Batteriepass und austauschbare Akkus
  - Kurz: Der Batteriepass ist der erste verbindliche digitale Produktpass der EU.
  - Zu tun: Batterien für E-Bikes und E-Scooter, Elektrofahrzeugbatterien und Industriebatterien über 2 kWh brauchen ab dem 18. Februar 2027 einen digitalen Batteriepass mit QR-Code.
  - Zu tun: Bereitstellen müssen ihn Hersteller und Importeure. Als Händler lassen Sie sich vom Lieferanten bestätigen, dass der Pass vorliegt.
  - Zu tun: Für Geräte mit eingebauten Akkus gelten ab demselben Tag Vorgaben zur Entnehmbarkeit und Austauschbarkeit der Batterien.

### 14. Digital product passport for textiles and furniture

- Id: `dpp`
- Applies when: `sells_eu & (has:textiles | has:furniture_wood)`
- Date: none yet (planned)
- Planning status: No fixed date yet. The EU Commission plans the legal act for textiles for 2027 and for furniture for 2028. The duty only starts after a transition period in each case.
- Scope: EU regulation, same across the EU
- Legal basis: Verordnung (EU) 2024/1781 (Ökodesign-Verordnung, ESPR)
- Summary: A product passport is only mandatory where an EU legal act requires it for the product group. So far only the battery passport is fixed.
- What to do:
  - Start collecting data from suppliers now: material composition, origin, certificates.
  - Store product data in a structured, machine-readable way.
  - Keep an eye on the legal act for your product group.
- Sources: [IHK Bodensee-Oberschwaben – Digitaler Produktpass](https://www.ihk.de/bodensee-oberschwaben/innovation/innovation-und-technologie/produktentwicklung/der-digitale-produktpass-6801576), [onlinemarktplatz.de – DPP-Fristen nach Produktgruppen](https://onlinemarktplatz.de/294244/dpp-fristen-produktgruppen/)
- German wording:
  - Titel: Digitaler Produktpass für Textilien und Möbel
  - Stand der Planung: Noch kein festes Datum. Die EU-Kommission plant den Rechtsakt für Textilien für 2027 und für Möbel für 2028. Die Pflicht beginnt jeweils erst nach einer Übergangsfrist.
  - Kurz: Ein Produktpass ist nur Pflicht, wenn ein EU-Rechtsakt ihn für die Produktgruppe vorschreibt. Fest steht bisher nur der Batteriepass.
  - Zu tun: Jetzt schon Daten von Lieferanten sammeln: Materialzusammensetzung, Herkunft, Zertifikate.
  - Zu tun: Produktdaten strukturiert und maschinenlesbar ablegen.
  - Zu tun: Den Rechtsakt für Ihre Produktgruppe im Blick behalten.

### 15. Producer responsibility for textiles and shoes (textile EPR)

- Id: `textile_epr`
- Applies when: `sells_eu & has:textiles`
- Date: none yet (planned)
- Planning status: Germany must pass a textile law by 17 June 2027. The take-back schemes must be operating by 17 April 2028 at the latest.
- Scope: EU directive, implemented per country (German law shown)
- Legal basis: Richtlinie (EU) 2025/1892
- Summary: It will affect everyone who places clothing, home textiles or shoes on the market in an EU country for the first time, including importers, own brands and online sellers from abroad.
- What to do:
  - There is no duty in Germany yet. Later: join a producer responsibility organisation and report quantities.
  - Start recording weight and material per item now.
  - Some EU countries already have their own rules. Check before shipping there.
- Sources: [Händlerbund – Textilgesetz und EPR](https://www.haendlerbund.de/de/ratgeber/branchen/textilgesetz-und-epr), [IT-Recht Kanzlei – Textilgesetz](https://www.it-recht-kanzlei.de/textilgesetz-pflichten-haendler.html)
- German wording:
  - Titel: Herstellerverantwortung für Textilien und Schuhe (Textil-EPR)
  - Stand der Planung: Deutschland muss bis zum 17. Juni 2027 ein Textilgesetz erlassen. Die Rücknahmesysteme müssen spätestens am 17. April 2028 arbeiten.
  - Kurz: Betreffen wird es alle, die Kleidung, Heimtextilien oder Schuhe erstmals in einem EU-Land auf den Markt bringen, auch Importeure, Eigenmarken und Onlinehändler aus dem Ausland.
  - Zu tun: In Deutschland besteht noch keine Pflicht. Später: einer Organisation für Herstellerverantwortung beitreten und Mengen melden.
  - Zu tun: Schon jetzt Gewicht und Material je Artikel erfassen.
  - Zu tun: Einzelne EU-Länder haben bereits eigene Regeln. Vor dem Versand dorthin prüfen.

## Outlook

- When `sells_eu & b2c`: Digital Fairness Act: on 11 November 2026 the EU Commission presented a proposal, among other things against manipulative design and subscription traps. This is not law yet. Source: [Ebner Stolz – Entwurf Digital Fairness Act](https://www.ebnerstolz.de/de/unser-angebot/leistungen/rechtsberatung/wirtschaftsrecht-commercial/digital-fairness-act-entwurf-115978.html)
  - German wording: Digital Fairness Act: Die EU-Kommission hat am 11. November 2026 einen Vorschlag vorgelegt, unter anderem gegen manipulative Gestaltung und Abofallen. Das ist noch kein Gesetz.

- When `sells_eu & has:electronics`: Cyber Resilience Act: from 11 December 2027, security requirements apply to products with digital elements. Source: [Händlerbund – Gesetzesänderungen 2027](https://www.haendlerbund.de/de/ratgeber/recht/gesetzesaenderungen-2027)
  - German wording: Cyber Resilience Act: Ab 11. Dezember 2027 gelten Sicherheitsanforderungen für Produkte mit digitalen Elementen.

- When `sells_eu & physical`: Ban on products made with forced labour: applies from 14 December 2027 to everyone who offers products in the EU. Source: [Händlerbund – Gesetzesänderungen 2027](https://www.haendlerbund.de/de/ratgeber/recht/gesetzesaenderungen-2027)
  - German wording: Verbot von Produkten aus Zwangsarbeit: gilt ab 14. Dezember 2027 für alle, die Produkte in der EU anbieten.

- When `sells_eu & physical & !(has:textiles | has:furniture_wood)`: Digital product passport for further product groups: dates only arise through separate legal acts per product group. Source: [onlinemarktplatz.de – DPP-Fristen nach Produktgruppen](https://onlinemarktplatz.de/294244/dpp-fristen-produktgruppen/)
  - German wording: Digitaler Produktpass für weitere Produktgruppen: Termine entstehen erst durch eigene Rechtsakte je Produktgruppe.
