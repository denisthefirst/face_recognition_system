# face_recognition_system
Project for Data Science class at HHN

# Projektstruktur

```plaintext
projekt/
├── data/
│   ├── faces/              # Ordner mit Unterordnern für jede Person
│   │   ├── person1/        # Bilder von Person 1
│   │   ├── person2/        # Bilder von Person 2
│   │   └── ...
│   └── embeddings.pkl      # Gespeicherte Gesichtseinbettungen
├── models/
│   ├── face_detection.py       # MTCNN-Implementierung
│   ├── face_recognition.py     # MobileNetV2-Implementierung
│   └── saved_models/           # Gespeicherte Modelle (z. B. MobileNetV2-Gesichtserkennung, MTCNN-Modell)
├── src/
│   ├── modelling/
│   │   ├── training.py             # Trainingsskript
│   │   └── inference.py            # Inferenzskript
│   ├── transformations/
│   │   ├── data_loading.py         # Datenladen
│   │   ├── data_preprocessing.py   # Datenvorverarbeitung
├── api/
│   ├── app.py                  # Flask-API
│   └── hass_integration.py      # Home Assistant Integration
├── app.py                       # Hauptanwendung
└── requirements.txt             # Projektabhängigkeiten
