![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)


# About me

My name is Lucas, I'm a Data Engineer based in São Paulo, SP.

I genuinely love working with data. Not just as a profession, but as a way of
making sense of things.

## About my repos

Instead of spreading my time across small, isolated projects, I build and maintain
a single end-to-end data platform running on my own home server. It's my
**homeprod**: real pipelines, on real schedules, processing data I actually use
day to day.

The platform is split into three repos, one per layer:

- [my_ingestion](link): ETL pipelines that extract and load data from external sources
- [my_analytics](link): dimensional modeling and data marts
- [my_orchestration](link): Airflow DAGs that schedule and tie everything together

Why not a monorepo? Each layer has its own lifecycle, dependencies and deploy
cadence, so keeping them separate mirrors how data teams usually split
responsibilities in production, while still working as one system.

Check out my [Tableau Public](https://public.tableau.com/app/profile/lcsprado/vizzes),
where I've been sharing visualizations since the beginning of my data career.
