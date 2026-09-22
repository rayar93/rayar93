# Alan Ray

Back-end and data engineering - pipelines, storage, search. CS senior at Appalachian State, graduating December 2026. Greenville, SC.

---

## Projects

**[game-score-aggregator-cloud-run](https://github.com/rayar93/game-score-aggregator-cloud-run)** - Aggregates and normalizes critic and user scores from IGDB, Steam, and Metacritic into a single weighted ranking across 300,000+ titles. Handles rate limits and title reconciliation across sources with incompatible scales. Graded on Cloud Run over Cloud SQL Postgres with scheduled ingestion via Cloud Run Jobs and Cloud Scheduler. Rebuilt after the course to serve a small SQLite snapshot from one Cloud Run container, taking hosting from ~$1/day to effectively $0. *Team project - CS 3537 Cloud Computing.*

**[dl-forecasting-classification-keras](https://github.com/rayar93/dl-forecasting-classification-keras)** - Two deep learning pipelines: bias correction of NOAA National Water Model streamflow forecasts (GRU, LSTM), and building damage classification from post-hurricane UAV imagery (MobileNet transfer learning). Reproducing the damage paper's methodology surfaced data leakage in its original evaluation split. *Team Project - CS 4440 Artificial Intelligence.*

**[ml-classification-regression-sklearn](https://github.com/rayar93/ml-classification-regression-sklearn)** - Two end-to-end pipelines: 4-class student performance classification (Logistic Regression, 54.4% accuracy) and auction verification regression (Random Forest, R²=0.991). scikit-learn, GridSearchCV, 10-fold CV. *Team project - CS 4440 Artificial Intelligence.*

**[asset-flip-game](https://github.com/rayar93/asset-flip-game)** - A 2D side-scrolling platformer in Godot 4. Real-time physics, state-driven enemy AI, and signal-driven event architecture across five playable levels. *Team project - CS 4800 Capstone Project.*

**[opencritic-scraper-analyzer](https://github.com/rayar93/opencritic-scraper-analyzer)** - Scrapes 10,000 OpenCritic titles and carries them through cleaning, exploration, and modeling in a single pipeline. Parses robots.txt at runtime and honors the published crawl-delay instead of hardcoding a rate. Percent-of-critics-recommend alone explains most of the critic score (R²=0.74); adding review count and release year moves it only to 0.75. Selenium, Protego, pandas, matplotlib, scikit-learn. *Solo project - CS 3435 Data Collection and Visualization.*

---

## Stack

- **Languages** - Python, Java, SQL, JavaScript, GDScript, C, C++
- **Cloud** - GCP (Cloud Run, Cloud SQL, Pub/Sub, Eventarc, Cloud Build, Artifact Registry, GKE)
- **Data** - Postgres, SQLite, Firestore, pandas, scikit-learn, Keras
- **Other** - Spring Boot, Flask, Docker, Kubernetes, ROS 2, Git, Linux

---

Open to software, backend, data, machine learning, IT, technical writing, cloud engineering and game dev roles.
