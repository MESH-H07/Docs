# MESH22 / H07
### Projektname: Familiar

## 1. Wer sind wir?
Wir sind ein Team aus fünf Karlsruher Informatikern, welche an der DHBW Karlsruhe gerade ihr 4. Semester antreten. <br>

<img src="https://github.com/MESH-H07/docs/blob/main/Team%20Image.jpg"/>

Wir sind: __Luca, Oliver, Lukas, Fabi und Jakob! (links -> rechts)__ 

## 2. Was ist das Problem?
Flüchtling oder Migrant zu sein, ist nicht einfach. Man hinterlässt einen großen Teil seines Lebens und sogar Familie, um sich in Sicherheit
zu bringen und oder ein neues Leben aufzubauen. Dabei betreten diese Leute häufig jedoch auf vielen Gebieten neues Terrain:

Sei es das hiesige soziale Zusammenleben, gerade in Deutschland aber auch eine Vielzahl komplizierter bürokratischer Hürden oder auch
scheinbar banale Dinge aus dem Alltag. Auch sozialer Anschluss ist ein wichtiges Thema, oder auch das Erlernen der Landessprache(n).

Es lassen sich jedoch durch etwas Hilfe einige Hürden und Hindernisse für Neuankömmlinge minimieren oder ganz nehmen.
Bisher existieren eine Vielzahl lokaler, regionaler und überregionaler Angebote in diesem Bereich,
seien es Integrationskurse, der Besuch von Sprachschulen oder der Beitritt in Sportvereine.

Jedoch fehlt bislang die Möglichkeit, sich zentral Informationen und Hilfe zu holen. Gerade im ländlichen Raum ist man
aufgrund der Vorurteile, räumlichen Distanzen, fehlender Kulturangebote und unzureichend ausgebauter Nahverkehrsmöglichkeiten
klar im Nachteil.

Eine große Hürde ist es auch, überhaupt einmal eine Ansprechperson, einen Anker in dem ganzen Wirr-Warr, zu bekommen.
Sicherlich ist es beruhigend und hilfreich zunächst eine Person an der Hand zu haben, welche ähnliches erlebt hat und
genauso sich in Deutschland einfinden musste. Nun kann sie aber ihr Wissen mit einer gewissen Vertrautheit
weiter geben und so effizient helfen, Fuß zu fassen.

Diese Probleme erfahren Migraten im Allgemeinen, aber gerade durch die aktuelle Flüchtlingslage in der Ukraine
verschärft sich diese Situation erneut und es kommen viele Menschen nach Deutschland, die sich mit genau diesen
Hürden konfrontiert sehen.

## 3. Wie wollen wir es angehen?
Vorab: Unsere Visionen, bisher gemachte Arbeit und Umsetzungen lassen sich unter [Implementierung](https://github.com/MESH-H07/docs#5-implementierung) finden.

Wir glauben, dass einer der wichtigsten Faktoren für die Integration __persönlicher Kontakt__ ist!
Eine vertraute und nahbare Ansprechperson zu haben ist wesentlich mehr wert, als kalte Fakten von einer Informationsstelle vorgekaut zu bekommen.

Deshalb wollen wir eben nicht nur einfach plump Informationen bereitstellen, sondern eine Plattform schaffen
für den sozialen Austausch und das Zusammenkommen, speziell zwischen Migraten und hilfsbereiten Mentoren.

Wir sehen für Einwanderer hauptsächlich folgende drei Hürden:
  1) Sprache
  2) Bürokratie
  3) Alltag und Zusammenleben

#### Mentoren
Das sind allesamt große und wichtige Themen!
Unsere Idee ist es deshalb, dass sog. "Mentoren", also entweder Einheimische oder bereits andere erfolgreich integrierte Migranten (möglicherweise mit ähnlichem Hintergrund), ihre Hilfe in diesen Bereichen anbieten, um es den Hilfesuchenden einfacher zu machen. Gerade letztere spielen für Neuankommene sicherlich eine wichtige Rolle, weil sie oft die gleiche Sprache sprechen und sich direkt einige Gemeinsamkeiten finden.

Wichtig ist dabei, dass Mentoren für Bürokratie allerdings eine Zertifizierung brauchen, weil Papierkram nicht selten rechts-relevante Themen behandelt.
Sie müssen einen Durchblick durch den Paragraphen-Dschungel Deutschland haben (gewisse Rechtsbereiche können beliebig komplex werden, sodass auch der Gesetzgeber mit seinem Durchblick Probleme haben kann) und rechts-sichere Hilfestellungen geben können.
Besonders für Alltagsthemen wie öffentlichen Transport, Einkauf etc. sind jedoch alle hilfsbereiten Personen dazu angehalten, ihre Hilfe anzubieten :)

Der Austausch kann auch App-intern in digitaler Form durch Chats stattfinden.

#### Events
Die Mentoren sollen aber nicht der einzige soziale Anknüpfpunkt sein! Ferner gibt es eine sog. eine Community-Page, wo gewisse Leute Events posten können,
an denen gerne teilgenommen werden darf. Häufig sind das speziell ausgelegte inklusive Veranstaltung. Dabei kann es sich um sämliche Formen von ungezwungenen Get-Togethers handeln, ob es nun Spieleabende, Kochveranstaltungen, Spaziergänge, Sommertage am See oder gemeinschaftliches Kicken handeln!

Sie werden gegliedert nach:
  1) Nähe (Nearby) - Radius selbst einstellbar
  2) In your District - gerade bei großen Städten mit weitreichenden Stadtteilen sinnvoll
  3) In your City - im Allgemeinen in einer Stadt

So können Leute aus der Stadt und auch aus dem Umland oder aus ländlichen Regionen mit gewisser Entfernung relevante und wahrnehmbare Angebote sichten.

## 4. Techstack
Unser eigener Anspruch an den Techstack war, dass er möglichst einfach aufzusetzen und zu warten sei und zugleich massiv Kosten für unseren Klienten bietet!
Da AWO kein kommerzielles Unternehmen ist, ist das Budget begrenzt und die Kosten sollten niedrig gehalten werden.

Wir konnten uns auf folgende Struktur einigen:
| Layer | Komponenten |
|-------|-------------|
| Frontend | - Ionic (Wrapper für React & TypeScript & Custom CSS) |
| Backend | - express.js (TypeScript) <br> - Prisma (Database Scheme) <br> - MySQL (Datenbank) |

## 5. Implementierung
Unsere visuelle Erarbeitung könnt ihr auf [Figma](https://www.figma.com/file/qxbdt9jJVTIHky4o3EQaTT/) betrachten!
Ziel war es, dies so weit wie möglich in der knappen Zeit in eine App zu gießen.

Es existierten im Übrigen auch Repositories für [Frontend](https://github.com/MESH-H07/Frontend) und [Backend](https://github.com/MESH-H07/Backend).
Wenn ihr also die Anwendung ausprobieren wollt, könnt ihr euch die beiden Projekte clonen und selbst bauen :)

## 6. Konkurrenzanalyse
Bei unserer Recherche konnten wir folgende bisherige Ansätze finden:
| Name  | Link  | Features | Downloads (2016) | Sprachenumfang |
|-------|-------|----------|------------------|----------------|
| Integreat | https://integreat-app.de/ | * Bereitstellung von Informationen in verschiedenen Sprachen | 10-50k | 6 Sprachen |
| Ankommen | https://ankommenapp.de/ | * generalistischer Ansatz (Deutsch lernen; Alltag; Asyl, Ausbildung und Arbeit | 100k-500k | 5 Sprachen |
| Welcome App Germany | https://play.google.com/store/apps/details?id=de.welcome_app_concept.welcome2germany&hl=en_US&gl=US | * Alltag <br> * Asyl-System und regionale Kontakte | 10k-50k | 6 Sprachen |
| Welcome to NRW | https://apkpure.com/welcome-to-nrw/de.nrw.welcometonrw | * FAQ <br> * Adresskatalog <br> * Phrasenbuch | 1k-5k | 4 Sprachen |

Neben eingeschränkten Sprachumfang, leiden die Umsetzungen auch unter geringer Reichweite und nur geringer Angebotsbreite. <br>
Keine der Apps jedoch bietet eine persönliche Komponente, ein wichtiger Schlüssel für eine erfolgreiche Integration!

Unsere Lösung soll eine große Bandbreite an Sprachen umfassen, die Mentoren werden unterschiedlichste Hintergründe haben und sind
zudem nicht nur bereit simple Informationen zu liefern, sondern die Neuankömmlinge auch an die Hand zu nehmen, um ihnen
direkt, individuell und verlässlich helfen zu können. Daneben erhalten sie auch attraktive Angebote für verschiedenste Aktivitäten
und können in direkten Austausch mit bereits erfolgreich integrierten Landsleuten treten. Damit sind wir bestehenden Angeboten in Sachen Sprachumfang und Angebot voraus!

## 7. Finanzierung
Die App selbst ist nicht monetarisiert, d.h. kein Bezahlmodell und auch keine Werbung. <br>
Das würde den eigentlichen Sinn etwas untergraben und unnötig aus schwierigen Situationen, welche
unser Projekt schließlich zu lösen versucht, Profit schlagen.

Die Finanzierung soll daher durch Fördertöpfe von Bund und Ländern, durch Sponsorenzahlungen von
Dachverbänden, gemeinnützigen Vereinen oder allgemein Sozialverbänden stattfinden. Die simple
Infrastuktur sorgt dafür, dass das Projekt sehr bezahlbar bleibt.

## 8. Marketingstrategie
Fernab von Monetarisierung, verfolgt das Marketing auch das Ziel, eine breite Audienz zu erreichen. <br>
Wenngleich kommerzieller Erfolg keine Rolle spielt, so besteht dennoch ein sehr großes Interesse daran, die App sehr bekannt zu machen. <br>
So erhöhen sich die Chancen, dass die Zielgruppe erreicht wird und auch genügend hilfsbereite Menschen auf die Plattform aufmerksam werden,
sodass das Konzept funktionieren kann. Auch lassen sich so Sponsoren finden.  

Da es sich hierbei um ein soziales Projekt handelt, halten wir Social Media tatsächlich für die richtige Plattform
und Influencer (im sozialen Bereich, mit entsprechender Community) mit angemessener Reichweite für das richtige
Sprachrohr.

Aber auch Erstanlaufstellen oder zentrale soziale Einrichtungen sollen dazu genutzt werden, gerade den Geflüchteten
das Program näher zu bringen.
