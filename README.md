# A. R. Ray

Back-end and data engineering - pipelines, storage, search. Recent CS graduate (Appalachian State, data science certificate),  based in Greenville, SC.

Most of what I build comes back to sorting and organizing the mounds of personal data I've accumulated over a rich digital life: photos, journals, listening 
history, things I meant to read, things I mean to cook. Taken together they are an interesting indexing problem - deduplication, embeddings, schema design 
across incompatible sources, and getting all of it to run cheaply enough to keep running as a personal project.

---

## Projects

**[game-score-aggregator-cloud-run](https://github.com/rayar93/game-score-aggregator-cloud-run)** - Aggregates and normalizes critic and user scores from IGDB, Steam, and Metacritic into a single weighted ranking across 300,000+ titles. Handles rate limits and title reconciliation across sources with incompatible scales. Cloud Run over Cloud SQL Postgres, scheduled ingestion via Cloud Run Jobs and Cloud Scheduler. *Team project - CS 3537 Cloud Computing.*

**[post-hurricane-aerial-damage-assessment](https://github.com/rayar93/post-hurricane-aerial-damage-assessment)** - UAV imagery damage classification. Reproducing the source paper's methodology surfaced data leakage in the original evaluation split. *Team Project - CS 4440 Artificial Intelligence.*

**[ml-classification-regression-sklearn](https://github.com/rayar93/ml-classification-regression-sklearn)** - Two end-to-end pipelines: 4-class student performance classification (Logistic Regression, 54.4% accuracy) and auction verification regression (Random Forest, R²=0.991). scikit-learn, GridSearchCV, 10-fold CV. *Team Project - CS 4440 Artificial Intelligence.*

**[asset-flip-game](https://github.com/rayar93/asset-flip-game)** - A 2D side-scrolling platformer in Godot 4. Real-time physics, state-driven enemy AI, and signal-driven event architecture across five playable levels. *Team Project - CS 4800 Capstone Project.*

**[opencritic-scraper-analyzer](https://github.com/rayar93/opencritic-scraper-analyzer)** - Scrapes 10,000 OpenCritic titles and carries them through cleaning, exploration, and modeling in a single pipeline. Parses robots.txt at runtime and honors the published crawl-delay instead of hardcoding a rate. Percent-of-critics-recommend alone explains most of the critic score (R²=0.74); adding review count and release year moves it only to 0.75. Selenium, Protego, pandas, matplotlib, scikit-learn. Solo project - CS 3435 Data Collection and Visualization.

---

## In progress

Three pieces of the same system, built as separate services rather than one monolith:

- **Timeline** - the past. Ingests a ~56 GB / 16k-file photo library plus journals and listening history into a searchable chronology. Local scan and perceptual-hash dedup, then multimodal embeddings for semantic search. SQLite locally, Vertex AI for enrichment.
- **Task system** - the future. Structured to-dos with phase, cadence, and floor/ceiling logic. Has recipe and shoppling-list tool module.
- **Recommender** - taste. Cross-category ratings for films, games, books, and shows, using preference in one category to inform suggestions in another. Feeds on a scraper module.

---

## Stack

- **Languages** - Python, Java, SQL, JavaScript, GDScript
- **Cloud** - GCP (Cloud Run, Cloud SQL, Pub/Sub, Eventarc, Cloud Build, Artifact Registry, GKE)
- **Data** - Postgres, SQLite, Firestore, pandas, scikit-learn, Keras
- **Other** - Spring Boot, Flask, Docker, Kubernetes, ROS 2, Git, Linux

---

Open to software, backend, data, and cloud engineering roles.
