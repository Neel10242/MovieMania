# MovieMania

MovieMania is a PostgreSQL-based movie database project developed as a course group project.

## Features

- Relational database design for movies, genres, cast, reviews, users, administrators, and watchlists.
- SQL queries for retrieving and analyzing movie data.
- PostgreSQL integration using Python.
- Movie information and poster integration using OMDb and TMDB APIs.
- ERD and BCNF analysis.

## Technologies

- PostgreSQL
- Python
- SQL
- OMDb API
- TMDB API

## Repository Structure

```text
MovieMania/
├── sql/
│   ├── schema.sql
│   ├── queries.sql
│   └── advanced_queries.sql
├── scripts/
│   ├── import_cast_omdb.py
│   ├── import_director_writer_omdb.py
│   ├── sync_tmdb_posters.py
│   └── show_movie_posters.py
├── docs/
│   └── ERD_BCNF_Proof.pdf
├── .env.example
├── .gitignore
├── requirements.txt
└── README.md
```
