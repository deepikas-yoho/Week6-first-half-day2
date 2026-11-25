# Week 6 - Day 2 (First Half)

```bash
pip install -r requirements.txt
python task1_ann_search.py          # Task 1 -> prints timings, saves recall_vs_time.png

docker compose up -d                # Task 2 DB (pgvector/pgvector:pg16)
python task2_pgvector.py            # Task 2 + bonus
# or run task2_schema.sql in psql:  docker exec -it pgvector-db psql -U postgres -d vectordb
```
Take screenshots of the three EXPLAIN ANALYZE outputs (no index / HNSW index / filtered) for submission.
