#
########################################################################
#         # Smolit #
#           S PECH_RECOGNITION
#           M ODULAR_FRAMEWORK
#           O PEN_SOURCE
#           L OCAL_ARTEFICIAL_INTELLIGENC
#           I nteractive_AI_Assistants
#           T oolchain_Optimization
########################################################################
# Smolit AppIamge
# AppImage combines all Smolit-CLI-Tools
########################################################################
# Actual development version:
# Version: smolit-app-image v-0.0.0
# Athor: SamSilnig
########################################################################
#



# +++++ TEXT ÜBER SMOLIT +++++




## Smolit-CLI-Tools





## ProjektStrucktur:

Smolit-CLI-Tool.AppDir/
├── AppRun (ein Skript oder symbolischer Link zu Ihrem Hauptprogramm)
├── meinprogramm.desktop (Desktop-Datei für Ihr Programm)
├── meinprogramm.png (Icon-Datei)
└── usr/
    ├── bin/ (hier liegt Ihr ausführbares Programm)
    ├── lib/ (hier liegen benötigte Bibliotheken)
    └── share/ (weitere Ressourcen)


## Um ein Smolit-CLI-Tool AppImage unter Linux zu erstellen, folgen Sie diesen Schritten:

## Vorbereitung

    Entwickeln Sie Ihr Programm: Stellen Sie sicher, dass Ihr Programm unter Linux läuft.
    Installieren Sie notwendige Abhängigkeiten: Abhängig von Ihrem Linux-Distribution müssen Sie möglicherweise zusätzliche Pakete installieren, um AppImages zu erstellen.

## AppImage Erstellung

    Sammeln Sie alle Abhängigkeiten: Ihr AppImage muss alle Abhängigkeiten beinhalten, die nicht standardmäßig auf den meisten Linux-Systemen vorhanden sind. Verwenden Sie Tools wie "ldd" um die Abhängigkeiten Ihres Programms zu überprüfen.

    Erstellen Sie ein AppDir: Ein AppDir ist ein Verzeichnis, das die Struktur Ihres AppImages darstellt. Es sollte folgende Struktur haben:

    Smolit-CLI-Tool.AppDir/
    ├── AppRun (ein Skript oder symbolischer Link zu Ihrem Hauptprogramm)
    ├── meinprogramm.desktop (Desktop-Datei für Ihr Programm)
    ├── meinprogramm.png (Icon-Datei)
    └── usr/
        ├── bin/ (hier liegt Ihr ausführbares Programm)
        ├── lib/ (hier liegen benötigte Bibliotheken)
        └── share/ (weitere Ressourcen)

Erstellen Sie das AppImage: Verwenden Sie das appimagetool (von https://github.com/AppImage/AppImageKit herunterladbar), um das AppDir in ein AppImage zu konvertieren. Führen Sie dazu folgenden Befehl aus:

````
appimagetool MeinProgramm.AppDir
````

Dies wird eine Datei MeinProgramm.AppImage erstellen.


## Verwendete Open Source Tools:

Kaldi                   Speech_Recognition                  https://github.com/kaldi-asr/kaldi
LocalAI                 API-KEY                             https://github.com/mudler/LocalAI
gpt-engineer            AGENT                               https://github.com/AntonOsika/gpt-engineer
Langchain               CHAIN                               https://github.com/langchain-ai/langchain
Shell-GPT               AGENT                               https://github.com/TheR1D/shell_gpt
