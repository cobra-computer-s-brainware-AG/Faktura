# Release Notes | Faktura

> [!NOTE]
> Die Aktuelle Version kann [hier](https://github.com/cobra-computer-s-brainware-AG/Faktura/raw/refs/heads/master/Current/Cobra.Faktura.Installer.6.0.1.107.zip) heruntergeladen werden.
 

## 6.0.1.107

* ### NEU: Twingle API (Fundraising)
  Neu können Spenden via. Twingle API Konfiguriert und Importiert werden.

* ### NEU: Excel und CSV Import (Fundraising)
  Neu können Spenden via. Excel und CSV Konfiguriert und Importiert werden. 

* ### NEU: Neuer Client-Setup für cobra 25.2 oder neuer
  Für cobra 25.2 oder neuer verwenden Sie das neue `Cobra.Faktura.ClientSetup.64.v2.msi`. Zudem wurde das Installer Bild überarbeitet. 

* ### NEU: Nur noch Sammelmappe im Ausgabeort
  Wird das Dokumentenfeld konfiguriert, wird nur noch die Sammelmappe am Ausgabeort abgelegt. Alle Rechnungen werden im DMS gespeichert.

* ### NEU: Schaltflächenbefehl mit vordefiniertem Format
  Neu gibt es in den Schaltflächenbefehlen `Sammelrechung mit vordefiniertem Format`.

* ### NEU: Geburtsdatum, Gebühr, Netto, Source_url und CustomParameter
  Neu lassen sich das Geburtsdatum, Gebühr, Netto, Source_url sowie CustomParameter in RaiseNow konfigurieren.

* ### NEU: RaiseNow Adressen Recherchieren
  Neu können angelegte RaiseNow-Adressen recherchiert werden. Ausserdem kann ausgewählt werden, dass Dubletten nicht überschrieben werden.

* ### NEU: RaiseNow Standard Werte   
  Neu können für (Insert Only) Standardwerte für die Adresse konfiguriert werden. Zudem stehen 

* ### Bugfixes und Diverse
  Der RaiseNow Bug wurde behoben.

  Der Lizensierung Bug wurde behoben.

  Der Referenznummer Bug mit Adressfeldern wurde behoben. 

  Performmance Optimierung.

  Die ProgressBar wurde optimiert.

  Die PDF-Bereinigung lässt sich in der Faktura.ini über CleanOutput = False unterbinden

  Kunden Plugin wurde in BESR Plugin umbenannt. 
 
  
## 6.0.0.9

* ### NEU: History
  Neu gibt es für den RaiseNow- und Camt-Import eine Historie-Protokollierung.

* ### NEU: Weitere Kontakt Felder
  In den Einstellungen unter Kontakteintrag können weitere Kontaktfelder befüllt werden. 

* ### Bugfixes und Diverse

  Der Fehler bei den Folgebefehlen der Schaltflächen wurde behoben. (1.0.0.7)

  Die Anzahl der CAMT-Dateien wurde optimiert. 

  Div. Performance Optimierungen.

  Die Installer für cobra Faktura wurden signiert.

  CAMT053 Adresslogik wurde angepasst. 

## 6.0.0.8

* ### Bugfixes und Diverse

  Die Funktion `Fakturieren` wurde in `Serienrechnung` umbenannt.

  Der Block für die Referenznummer wurde überarbeitet.

  Das Feld `Nicht verrechnen` für die Datenaufbereitung wurde in die Filterfunktion integriert.

  Beim CAMT Importer wurde ein neues Feld `EndToEndId` für CH-DD ergänzt.

## 6.0.0.7

* ### NEU: Einzelrechnung
  Neu lässt sich eine Einzelrechnung aus dem aktuellen Datensatz erstellen.

* ### NEU: Punkt Platzhalter-Trennzeichen
  Neu wird als Platzhalter-Trennzeichen neben dem Doppelpunkt auch ein Punkt unterstützt.
 
* ### Bugfixes und Diverse

  Der Filter Bug wurde behoben. 

## 6.0.0.6

* ### Bugfixes und Diverse 

  Die Rechnungsnummer kann wieder konfiguriert werden.

  Der UserManagement Bug bei Neuinstalationen wurde behoben. 

  Der Auswahldruck wird abgekündigt und ist kein Pflichtfeld mehr. 

  Div. Performance Optimierungen.


## 6.0.0.5

* ### Bugfixes und Diverse
 
  Der Bug mit Öffentlichen Gruppenkontakte wurde behoben.  


## 6.0.0.4

* ### Bugfixes und Diverse

  Die Faktura Fenster wurden Optisch überarbeitet.  


## 6.0.0.3

* ### Bugfixes und Diverse

  Der Bug bei der Zuweisung der Benutzerlizenz wurde behoben.

  Die Faktura Fenster wurden Optisch überarbeitet.  


## 6.0.0.2

* ### NEU: RaiseNow Excel
  Neu kann RaiseNow auch als Excel Importiert werden. 

* ### Bugfixes und Diverse

  Der MessageBox Bug wurde behoben. 

  Die Faktura Fenster wurden Optisch überarbeitet. 


## 6.0.0.0

* ### NEU: RaiseNow API  
  Neu kann RaiseNow via. API Importiert werden. 

* ### NEU: Neue Platzhalter  
  Neu sind die Platzhalter `CurUserName` und `CurUserShortName` verfügbar.

* ### NEU: Cobra-Feldformate  
  Neu werden die Cobra-Feldformate unterstützt.

* ### Bugfixes und Diverse

  Ablösung von Cobra CRM PRO 2020 durch eine neue Version.
 
  Die Validierung wurde optimiert.

  Alle Fenster wurden auf WPF umgestellt.

  


 

  
