# Wichtige Punkte der Veröffentlichung der Android-Anwendung für den Play Market

Sie sollten mit der Registrierung eines Entwicklerkontos beginnen [Dokumentation](https://support.google.com/googleplay/android-developer/answer/6112435). Es ist wichtig, ein **organisatorisches** Entwicklerkonto zu registrieren, nicht ein persönliches Entwicklerkonto.

Der Prozess zum Erstellen einer neuen Anwendung wird in der Google-Hilfe [Dokumentation](https://support.google.com/googleplay/android-developer/answer/9859152) beschrieben.
Im Wesentlichen müssen Sie sich durch mehrere Formulare klicken und Fragen zum Zweck des Antrags sowie zur Einhaltung zahlreicher rechtlicher Anforderungen beantworten.
Um die Anwendungsseite zu gestalten, müssen Sie Screenshots vom Gerät und andere grafische Ressourcen vorbereiten.

Wichtige Hinweise, die beachtet werden müssen. Ohne sie wird Ihnen die Veröffentlichung verweigert. Denken Sie daran, dass die Bewerbung vor der Veröffentlichung von aufmerksamen und wählerischen Personen bei Google überprüft wird.

1. Beim Entwerfen einer Anwendungsseite ist es wichtig, Screenshots hochzuladen, die speziell aus Ihrer Anwendung stammen. Sie bestehen die Prüfung nicht, wenn die Anwendungsoberfläche nicht die Bildschirme enthält, die Sie in den Screenshots bereitgestellt haben.
2. Wenn Sie die betreffende Funktion **Lokale Benachrichtigungen** anfordern, müssen Sie für den Abschnitt **Berechtigungen für Vordergrunddienste** ein Video vom Bildschirm aufnehmen und den folgenden Text laut sagen: „Wir verwenden Berechtigungen für Vordergrunddienste für.“ ein Hintergrunddienst zum Empfangen von Benachrichtigungen von unserem Videoserver, wenn kein Internet verfügbar ist. Dies ist ein Ersatz für Push-Benachrichtigungen für ein lokales Netzwerk.
3. Geben Sie im Abschnitt **Werbe-ID** an, dass Sie die Werbe-ID für **Analysen** verwenden.
4. Für die Abschnitte **Datensicherheit** und **Datenschutzrichtlinie** müssen Sie den Text der Datenschutzrichtlinie **auf Ihrer Website** platzieren und einen Link zu dieser Seite bereitstellen.
5. Das Ausfüllen des Abschnitts **Inhaltsbewertungen** ist erst möglich, nachdem die Anwendungsassembly in den Release-Entwurf hochgeladen wurde.
6. Wenn Ihre Anwendung keinen Demoserver hat, benötigt Google möglicherweise ein Testkonto, um die Anwendung zu überprüfen. Übergeben Sie ihnen diese Daten, um eine Verbindung herzustellen: URL http://136.243.144.109:8000/asip-api, Login-Root, Passwort Root.
7. Wenn Sie ein persönliches Konto anstelle eines Organisationskontos registriert haben, müssen Sie vor der Veröffentlichung der Bewerbung einen geschlossenen Test durchführen. Mindestens 20 Geräte müssen mindestens 14 Tage am Stück daran teilnehmen. Das Testen an Simulatoren wird nicht funktionieren, es werden echte Geräte benötigt. Google schlägt vor, sie fast auf der Straße zu suchen, bei Freunden, Bekannten und in Foren nach Freiwilligen zu suchen. Sie müssen in der Konsole eine Liste der Tester-Gerätekonten erstellen. Nachdem Sie die Anwendung im geschlossenen Testkanal veröffentlicht haben, senden Sie den Testern einen Link zur Anwendung, damit sie diese installieren können. Details [Dokumentation](https://support.google.com/googleplay/android-developer/answer/14151465). Die absurdeste Forderung.

_Stellen Sie Fragen zu unklaren Aspekten der Veröffentlichung und wir werden diese Anleitung umgehend mit Antworten ergänzen_