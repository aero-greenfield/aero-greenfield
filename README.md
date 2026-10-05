### Aero Greenfield

TIM student at UC Santa Cruz, class of 2028. I'm looking for summer 2027 internships
in backend, data, or analytics engineering.

I'm the sole engineer on [Botaniks](https://github.com/aerogreenfield/matcha-inventory-system),
a production inventory and batch-production tracker for a small matcha wholesaler. It
replaced manual spreadsheet tracking of 70+ raw materials and 45 products for a 6-person
team, and has been running in production since June 2026.

Most of what I actually do on it is find and fix bugs that only show up under real use:
a production race condition between two Gunicorn workers that could double-deduct stock,
a float-rounding bug that wrongly rejected a 176 lb order against exactly 176 lb of
stock, and a handful of N+1 query patterns. All of it is written up in the repo's
[engineering decisions doc](https://github.com/aerogreenfield/matcha-inventory-system/blob/main/docs/engineering-decisions.md),
if you want the reasoning and not just the result.

**Stack I work in:**

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-black?logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white)

**Currently:** Junior at UCSC, studying Technology & Information Management.
Coursework in Python, C, RISC-V assembly, discrete math, and linear algebra.

Reach me at aeroTNG@gmail.com or Linkedin: https://www.linkedin.com/in/aero-greenfield-7226a137a/
