# 🧠 SQL Practice Questions Repository

## Welcome!
This repo contains community-contributed SQL practice questions in JSON format.
You can easily add your own question and submit it via a Pull Request (PR).

## JSON Format

Each question must follow this structure:

```json
{
  "title": "Identify Faulty Tractors from IoT Alerts",
  "difficulty": "Hard",
  "description": "Given IoT sensor data from tractors, identify all tractors that have signaled an alert (IsAlerted = 1) for 3 or more consecutive dates.",
  "schema": "CREATE TABLE TractorAlerts (TractorID INTEGER, Date TEXT, IsAlerted INTEGER);\nINSERT INTO TractorAlerts VALUES (1, '1/1/2025', 1);\nINSERT INTO TractorAlerts VALUES (1, '2/1/2025', 1);\nINSERT INTO TractorAlerts VALUES (1, '3/1/2025', 1);",
  "expectedResult": {
    "columns": ["Faulty_TractorID"],
    "values": [[1]]
  },
  "contributor": {
    "name": "Your Name",
    "link": "https://www.linkedin.com/in/your-profile"
  }
}