src/
├── logging/
│ └── logger.py # Renamed from logging.py to avoid conflicts
├── exceptions/ # Plural form, lowercase
│ └── custom_exception.py # More descriptive name
├── utils/
│ └── utils.py
├── components/
│ ├── data_ingestion.py
│ ├── data_validation.py
│ ├── data_transformation.py
│ └── model_trainer.py # Renamed from data_train for clarity
├── config/ # New directory for configurations
│ └── config.py
└── pipeline/ # New directory for pipeline orchestration
└── training_pipeline.py
