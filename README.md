# \# 🗄️ SQL Portfolio — Ajala Boluwatife Oluwanifemi

# 

# A collection of SQL case studies built around real-world, business-style datasets — written and tested in \*\*PostgreSQL\*\* using \*\*pgAdmin\*\*. Each project tackles a set of business questions through joins, subqueries, CTEs, window functions, and aggregation logic, with the goal of demonstrating intermediate-to-advanced SQL problem solving rather than just query syntax.

# 

# Every project folder has its own README with the dataset schema, the full list of business questions, and the SQL concept used to answer each one.

# 

# \---

# 

# \## 📂 Projects

# 

# | Project | Dataset | Focus | Link |

# |---|---|---|---|

# | 🛒 Amazon E-Commerce Analysis | Amazon order/sales data | Advanced multi-table joins, CTEs, and aggregation across 11 business problems | \[View](./amazon-analysis) |

# | 📚 Library Management Analysis | Books, members, branches, issued/return status (6 related tables, ERD included) | Relational schema design and multi-table query logic | \[View](./library-analysis) |

# | 🎬 Netflix Content Analysis | Netflix titles dataset | Window functions, CTEs, string parsing (`unnest`, `split\\\_part`) across 15 business problems | \[View](./netflix-analysis) |

# | 🏬 Retail Sales Analysis | Retail sales transactions | Aggregation logic, GROUP BY granularity, business-question framing | \[View](./retail-analysis) |

# | 🎧 Spotify + YouTube Engagement | Cross-platform track engagement data | Window functions (`RANK`, `LAG`), subqueries, period-over-period analysis across 14 queries | \[View](./spotify-analysis) |

# | 🍽️ Zomato Restaurant Analysis | Food delivery dataset | Data cleaning (Python/Pandas), JOIN behavior, business-question SQL | \[View](./zomato-restaurant-analysis) |

# | ☕ Coffee Sales Analysis | Multi-table coffee sales schema | Window functions, joins, CTEs across progressively harder business problems | \*In progress\* |

# 

# \---

# 

# \## 🛠️ Tech Stack

# 

# \- \*\*PostgreSQL\*\* + \*\*pgAdmin\*\* — primary query environment

# \- \*\*Python / Pandas\*\* — data cleaning and CSV preprocessing where datasets required it

# \- \*\*Git / GitHub\*\* — version control and portfolio hosting

# 

# \## 🧠 Skills Demonstrated Across Projects

# 

# \- Joins (`INNER`, `LEFT`, `RIGHT`) and how join choice affects row granularity

# \- Window functions: `ROW\\\_NUMBER`, `RANK`, `DENSE\\\_RANK`, `PARTITION BY`, `LAG`

# \- Subqueries and CTEs, including layered/nested aggregates

# \- `GROUP BY` / `HAVING` filtering logic and aggregation granularity

# \- PostgreSQL-specific handling: `::NUMERIC` casting, `EXTRACT`, `TRIM`, date parsing

# \- Real-world data quality issues: trailing spaces, inconsistent formats, float precision

# 

# \## ▶️ How to Run

# 

# 1\. Clone this repository

# 2\. Open the project folder of interest in pgAdmin (or your preferred PostgreSQL client)

# 3\. Create the schema using the `CREATE TABLE` statements provided in that project's README

# 4\. Import the relevant CSV(s) into the tables

# 5\. Run the queries from the project's `.sql` file

# 

# \## 📫 Contact

# 

# \*\*Ajala Boluwatife Oluwanifemi\*\*

# LinkedIn: \[Ajala Boluwatife](https://www.linkedin.com/in/ajala-boluwatife-2b2854316)

# 

# Feel free to fork any of these projects for personal learning, or open an issue if you spot something worth improving.

