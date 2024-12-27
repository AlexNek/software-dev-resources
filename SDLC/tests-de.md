## Software-Tests

![image](tests.png)

Diese Tests werden während der "Test"-Phase des Software-Entwicklungslebenszyklus (SDLC) durchgeführt.

Softwaretests sind ein wesentlicher Bestandteil des SDLC, um die Zuverlässigkeit und Funktionsfähigkeit des Endprodukts sicherzustellen und den Erwartungen der Benutzer zu entsprechen. Dieser Prozess umfasst verschiedene Teststufen, Durchführungsmethoden und Perspektiven, die alle einen gründlichen Qualitätssicherungsprozess gewährleisten.

### Unit-Tests

- **Warum sie wichtig sind:** Unit-Tests bieten eine Grundlage, indem sie sicherstellen, dass einzelne Codeeinheiten korrekt funktionieren.
- **Fokus:** Kleinste testbare Einheiten wie Funktionen, Methoden oder Klassen.
- **Ziel:** Überprüfen, ob sich jede Einheit wie erwartet isoliert verhält.
- **Umfang:** Kleinste testbare Teile des Codes.
- **Beispiele:**
    * Testen, ob eine bestimmte Funktion die richtige Ausgabe für gegebene Eingaben zurückgibt.
    * Überprüfen, ob eine Klasse ihre Eigenschaften korrekt initialisiert.
    * Verifizieren, dass die Fehlerbehandlung innerhalb einer Methode wie vorgesehen funktioniert.
- **Testansatz:** Oft mit White-Box-Testtechniken durchgeführt, die sich auf den Code selbst konzentrieren.
- **Testmethode:** In der Regel automatisiert.

### Komponententests

- **Warum sie wichtig sind:** Komponententests überprüfen eine einzelne, in sich geschlossene Komponente der Anwendung, um sicherzustellen, dass sie korrekt funktioniert, bevor sie integriert wird.
- **Fokus:** Ein einzelnes, in sich geschlossenes Modul oder eine Komponente.
- **Ziel:** Die Funktionalität eines bestimmten Teils des Systems zu überprüfen, wenn es mit seinen unmittelbaren Abhängigkeiten interagiert.
- **Umfang:** Beschränkt auf die Komponente und ihre direkten Abhängigkeiten.
- **Beispiele:**
    * Testen eines Login-Moduls, einschließlich UI-Eingaben, Passwort-Hashing und Token-Erzeugung.
    * Testen einer API-Komponente, die für die Datenverarbeitung verantwortlich ist.
- **Testansatz:** Oft mit White-Box-Testtechniken durchgeführt, die sich auf die Komponente und ihre internen Abläufe konzentrieren.
- **Testmethode:** In der Regel automatisiert.

### Integrationstests

- **Warum sie wichtig sind:** Integrationstests bauen auf der Grundlage auf, indem sie überprüfen, dass die Einheiten im System reibungslos zusammenarbeiten.
- **Fokus:** Interaktionen zwischen verschiedenen Teilen des Systems.
- **Ziel:** Sicherstellen, dass die Komponenten wie vorgesehen zusammenarbeiten.
- **Umfang:** Größer als Unit-Tests, mit mehreren Einheiten oder Modulen.
- **Beispiele:**
    - Testen des Datenflusses zwischen verschiedenen Modulen.
    - Überprüfen, ob eine Datenbankinteraktion innerhalb des Systems korrekt funktioniert.
    - Überprüfen der Integration einer Benutzeroberfläche mit Backend-Diensten.

### Benutzeroberflächentests (UI-Tests)

- **Warum sie wichtig sind:** UI-Tests stellen sicher, dass die Benutzeroberfläche korrekt funktioniert und gut reagiert.
- **Fokus:** Die Elemente der Benutzeroberfläche und ihre Interaktionen.
- **Ziel:** Überprüfen, ob sich die Benutzeroberfläche wie erwartet verhält und Benutzer effektiv mit ihr interagieren können.
- **Umfang:** Bestimmte UI-Elemente oder gesamte Bildschirme.
*  **Beispiele:**
    - Testen, ob Schaltflächen, Menüs und Formulare wie erwartet funktionieren.
    - Überprüfen des UI-Layouts und der Reaktionsfähigkeit auf verschiedenen Bildschirmgrößen.
    - Testen des Navigationsflusses durch die Anwendung.
- **Testansatz:** Oft mit Black-Box-Testtechniken durchgeführt, die sich ausschließlich auf die Benutzeroberfläche konzentrieren, wie sie ein Endbenutzer sehen würde.
- **Testmethode:** In der Regel werden Tests automatisiert, aber auch manuelle Tests sind üblich, insbesondere während der Entdeckungsphase.

### Benutzerakzeptanztests (UAT)

- **Warum sie wichtig sind:** Benutzerakzeptanztests sind der letzte Schritt, um sicherzustellen, dass das System die Bedürfnisse und Erwartungen der Benutzer erfüllt.
- **Fokus:** Perspektive und Zufriedenheit des Endbenutzers sowie Übereinstimmung mit den Geschäftsanforderungen.
- **Ziel:** Feststellung, ob die Software den Bedürfnissen und Erwartungen der Benutzer entspricht.
- **Umfang:** Das gesamte System oder bestimmte Funktionen.
- **Beispiele:**
    - Echte Benutzer testen die Software in einer realistischen Umgebung.
    - Geschäftsinteressenten überprüfen, ob die Software ihre Anforderungen erfüllt.
    - Überprüfen, ob die Benutzeroberfläche intuitiv und einfach zu bedienen ist.
- **Testansatz:** Mit Black-Box-Testtechniken, bei denen der Anwender als Endnutzer und nicht als Software-Ingenieur agiert.
- **Testmethode:** In der Regel manuelle Tests durch echte Benutzer, aber auch automatisierte Testabläufe zur Validierung von Geschäftsfällen können enthalten sein.

## Funktionales Testen

- **Was es ist:** Funktionales Testen überprüft, ob jede Funktion oder jedes Merkmal der Software gemäß ihren Spezifikationen funktioniert. Es konzentriert sich auf die Benutzeroberfläche und darauf, was der Benutzer tut, um eine Aktion durchzuführen. Es ist eine Art von Test, die auf verschiedenen Ebenen, Ansätzen und Methoden anwendbar ist.
- **Warum es wichtig ist:** Funktionales Testen stellt sicher, dass sich das System aus der Perspektive des Benutzers wie erwartet verhält und alle spezifizierten Funktionen korrekt funktionieren. 
- **Fokus:** Benutzerinteraktionen und Testen der Ausgaben definierter Funktionen und Merkmale in Bezug auf spezifizierte Eingaben.
- **Ziel:** Sicherstellen, dass die Funktionalität des Systems den Erwartungen der Benutzer entspricht.
- **Umfang:** Anwendbar auf verschiedenen Ebenen, von einzelnen Einheiten bis zum gesamten System.
- **Beispiele:**
    * Überprüfen, ob die Schaltfläche "In den Warenkorb legen" auf einer E-Commerce-Website Artikel korrekt zum Warenkorb des Benutzers hinzufügt.
    * Überprüfen, ob ein Login-Bildschirm die Benutzeranmeldeinformationen validiert, um Zugang zum System zu gewähren.
    * Überprüfen, ob ein Filter auf einem Dashboard nur die relevanten Daten anzeigt.

## Zusätzliche Testarten

* **Dauertest:**
    * **Was es ist:** Ein Dauertest (manchmal auch Ausdauertest genannt) testet die Stabilität des Systems über einen längeren Zeitraum.
    * **Warum es wichtig ist:** Es stellt sicher, dass keine Speicherlecks oder andere Probleme auftreten, die im Laufe der Zeit auftreten.
    * **Wie es passt:** Es kann auf System- oder Komponententests angewendet werden.
* **Genehmigungstest:**
    * **Was es ist:** Tests, die überprüfen, ob die Ausgabe einer Funktion oder Komponente mit der zuvor "genehmigten" Ausgabe (einer Basislinie) übereinstimmt.
    * **Warum es wichtig ist:** Es hilft, unbeabsichtigte Änderungen der Ausgabe zu identifizieren, wenn Änderungen vorgenommen werden.
    * **Wie es passt:** Kann auf der Ebene von Unit- oder Komponententests verwendet werden.
* **Leistungstest:**
    * **Was es ist:** Leistungstests bewerten, wie die Software unter Last oder Stress funktioniert.
    * **Warum es wichtig ist:** Es stellt sicher, dass die Anwendung schnell, skalierbar und realistische Benutzerlasten bewältigen kann.
    * **Wie es passt:** Oft auf System- oder End-to-End-Tests angewendet.
* **Explorativer Test:**
    * **Was es ist:** Eine Testmethode, bei der Tester die Software frei erkunden, um Fehler zu finden, ohne vordefinierte Testfälle.
    * **Warum es wichtig ist:** Es hilft, unerwartete Probleme aufzudecken und kreativen Input zu liefern.
    * **Wie es passt:** Oft auf UI-, Systemtests und während der Benutzerakzeptanz angewendet.
* **Regressionstest:**
    * **Was es ist:** Tests, die bestehende Testfälle erneut ausführen, um sicherzustellen, dass neue Änderungen oder Fehlerbehebungen keine neuen Probleme (oder "Regressionen") in der bestehenden Funktionalität eingeführt haben.
    * **Warum es wichtig ist:** Verhindert, dass zuvor funktionierende Teile bei Änderungen beschädigt werden.
    * **Wie es passt:** Kann auf jeder Testebene (Unit, Integration, System) durchgeführt werden, oft automatisiert.
* **Rauchtest (Build Verification Test):**
    * **Was es ist:** Ein schneller Satz grundlegender Tests, um die grundlegende Funktionalität der Software zu überprüfen, die nach einer Codeänderung durchgeführt wird, um zu bestätigen, dass die wichtigsten Teile funktionieren.
    * **Warum es wichtig ist:** Stellt sicher, dass das System stabil ist, bevor eine gründlichere Prüfung beginnt.
    * **Wie es passt:** Oft als schnelle Überprüfung von Systemtests nach einer Bereitstellung durchgeführt.
* **Verstandestest:**
    * **Was es ist:** Ähnlich wie ein Rauchtest, konzentriert es sich auf kritische Funktionalität, testet jedoch spezifische Bereiche, die sich geändert haben.
    * **Warum es wichtig ist:** Eine schnelle Überprüfung, um sicherzustellen, dass die geänderten Teile stabil sind.
    * **Wie es passt:** Oft als Teil von Systemtests oder nach der Bereitstellung einer Fehlerbehebung durchgeführt.
* **Lasttest:**
    * **Was es ist:** Lasttests überprüfen, wie das System funktioniert, wenn es gleichzeitig von vielen Benutzern verwendet wird.
    * **Warum es wichtig ist:** Es identifiziert Leistungs- und Skalierbarkeitsprobleme unter Stressbedingungen.
    * **Wie es passt:** In der Regel auf Systemebene angewendet.

## Wichtige Unterschiede zusammengefasst

| Funktion                       | Unit-Tests                | Komponententests            | Integrationstests                | Systemtests (End-to-End) | UI-Tests                    | Benutzerakzeptanztests       |
|-------------------------------|---------------------------|---------------------------|----------------------------------|---------------------------|----------------------------|----------------------------|
| **Fokus**                     | Einzelne Einheiten          | Einzelne Komponenten     | Interaktionen zwischen Komponenten | Gesamte Anwendung         | Benutzeroberflächenelemente    | Perspektive des Endbenutzers       |
| **Umfang**                     | Kleinste Codeeinheiten       | Einzelne Komponente & Abhängigkeiten | Bestimmte Integrationen           | Gesamtes System oder Funktionen| UI-Elemente oder Bildschirme      | Gesamtes System oder geschäftskritische Funktionen|
| **Ziel**                      | Verhalten einzelner Einheiten  | Funktion einzelner Komponenten| Sicherstellen, dass Komponenten zusammenarbeiten | Gesamtes System aus Benutzersicht überprüfen | Verhalten und Reaktionsfähigkeit der Benutzeroberfläche überprüfen  | Erwartungen und Bedürfnisse der Benutzer sowie den Geschäftsfall erfüllen    |
| **Durchgeführt von**               | Entwickler, automatisiert     | Entwickler, oft automatisiert   | Entwickler/Tester, oft automatisiert| Tester, automatisiert         | Entwickler/Tester, oft automatisiert | Endbenutzer oder Interessenträger    |
| **Testansatz**          | White Box                 | White Box                 | White/Black Box                | Black Box                  | Black Box                   | Black Box                   |
| **Testmethode**             | Automatisiert                | Automatisiert                 | In der Regel automatisiert                | Hauptsächlich automatisiert (mit einigen manuellen) |  In der Regel automatisiert (mit einigen manuellen)    | Hauptsächlich manuell (manchmal automatisiert)     |

**Testmethoden und -ansätze:**

* **Manuelles Testen:** Tests, die von Menschen ausgeführt werden, ideal für Benutzerfreundlichkeit, komplexe Szenarien und exploratives Testen.
* **Automatisiertes Testen:** Tests, die von Skripten/Tools ausgeführt werden, effizient für Regression und wiederholbare Tests.
* **White-Box-Testen:** Testen basierend auf internem Code und Logik, verwendet für Unit-, Komponenten- und einige Integrationstests.
* **Black-Box-Testen:** Testen basierend auf Eingaben/Ausgaben, verwendet für System-, UI- und Akzeptanztests sowie einige Integrationstests.

**Im Wesentlichen:**

* **Unit- und Komponententests** stellen die Richtigkeit einzelner Codes und Komponenten sicher und bieten eine Grundlage für Tests.
* **Integrationstests** überprüfen die Interaktionen zwischen Systemteilen und konzentrieren sich auf Datenflüsse, Schnittstellen und Abhängigkeiten zwischen Komponenten.
* **Systemtests (End-to-End)** bieten einen umfassenden Überblick und stellen sicher, dass das System als Ganzes aus der Perspektive des Endbenutzers korrekt funktioniert und Benutzer-Workflows simuliert.
* **UI-Tests** konzentrieren sich speziell auf die Benutzeroberfläche und stellen deren Reaktionsfähigkeit und korrektes Verhalten sicher.
* **Benutzerakzeptanztests** bieten die endgültige Validierung durch Endbenutzer und Geschäftsbeteiligte.
* **Funktionales Testen** stellt sicher, dass alle Funktionen aus der Sicht des Benutzers funktionieren.
* **Zusätzliche Testarten** erfüllen spezifische Anforderungen während verschiedener Entwicklungsphasen und auf verschiedenen Testebenen.

Durch die Implementierung dieser verschiedenen Testarten und -methoden und das Verständnis ihrer Rollen im SDLC können Sie ein robusteres, zuverlässigeres und benutzerfreundlicheres Softwareprodukt erstellen.