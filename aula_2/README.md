
## Dicionário de Dados

| Campo | Tipo | Descrição |
|-------|------|-----------|
| id | int64 | Identificador do paciente |
| dataset | string | Origem do caso (Cleveland, Hungarian, Switzerland, VA Long Beach) |
| age | int64 | Idade em anos |
| sex | string | Sexo (Male/Female) |
| cp | string | Tipo de dor no peito (typical angina, atypical angina, non-anginal, asymptomatic) |
| trestbps | float64 | Pressão arterial em repouso (mmHg) |
| chol | float64 | Colesterol sérico (mg/dl) |
| fbs | object | Glicemia em jejum > 120 mg/dl (True/False) |
| restecg | string | ECG em repouso (normal, st-t abnormality, lv hypertrophy) |
| thalch | float64 | Frequência cardíaca máxima alcançada |
| exang | object | Angina induzida por exercício (True/False) |
| oldpeak | float64 | Depressão do ST induzida por exercício (unidades "ST depression") |
| slope | string | Inclinação do segmento ST de pico (upsloping, flat, downsloping) |
| ca | float64 | Número de vasos principais coloridos por fluoroscopia (0–3) |
| thal | string | Estado talassêmico (normal, fixed defect, reversable defect) |
| num | int64 | Diagnóstico (0 = sem doença; 1–4 = presença) |
