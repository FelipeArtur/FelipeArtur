<img src="assets/signal.svg" alt="Felipe Artur — Computer Engineer, Salvador, Bahia" width="100%">

Computer Engineer. I work across the whole stack of a product that touches the
physical world: the firmware on the board, the service that collects what it
measures, and the interface where someone finally reads it.

That range is the point. Reading a datasheet to write a driver, designing an
LVGL screen that runs on a microcontroller, standing up a Django or Flask API,
building a React dashboard, modelling data so a manager can act on it — these
have been different weeks of the same job, and the interesting problems usually
sit where two of them meet.

**Open to work**, in software development or data, in Salvador or remote.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-felipeartur-C62828?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/felipeartur/)
[![Email](https://img.shields.io/badge/Email-felipe.artur.ml@gmail.com-C62828?style=flat-square&logo=gmail&logoColor=white)](mailto:felipe.artur.ml@gmail.com)

---

### What I shipped

907 commits across 11 production projects at SENAI CIMATEC, from October 2023 to
July 2026. The ones I'd point at:

- The **interface of a medical vacuum system** — 245 commits as lead and
  maintainer. LVGL on an STM32H753, a UART protocol with CRC-16, and a desktop Qt
  simulator that let the screen be built and tested without the board.
- A **power datalogger that ran two years in the field** — 64 of its 73 commits.
  Modbus RTU over RS-485 into a cloud time-series database, with a disk queue:
  the reading is timestamped at the source and only leaves disk after the write
  is confirmed, so the series survives a network outage without a gap or a
  duplicate.
- The **ground station dashboard of a nanosatellite** — 183 commits, ~81% of it.
  A refactor separating visual config from data mapping removed ~2,900 duplicated
  lines across six sensor screens.
- The **first management BI dashboard its department had**, in Power BI with DAX
  written by hand. It was adopted, and a system was later built on top of it.

### Where I've worked

| | |
|---|---|
| **Embedded** | C++17 on STM32, FreeRTOS, Zephyr, LVGL interfaces, drivers written from datasheets, MISRA C++, serial protocols with CRC-16 |
| **Web and backend** | TypeScript, React, Django REST, Flask, PostgreSQL, SQLite, JWT authentication |
| **Data** | SQL by hand, relational modelling, pandas, Power BI and DAX, InfluxDB time series, TensorFlow and PyTorch, digital signal processing in MATLAB |
| **Infrastructure** | Linux, Docker, systemd, embedded Linux on Toradex, shell scripting, CI pipelines |

Also: Unreal Engine and VR, from undergraduate research.

### Things I built and kept

- **[BrokerShark](https://github.com/FelipeArtur/BrokerShark)** — a personal
  finance ledger, fully local. SQL written by hand: versioned schema,
  forward-only migrations with a log table, and the financial invariants living
  as an executable query the audit runs against the real database. Money in
  integer cents, no floats in the ledger.
- **[nb2pdf](https://github.com/FelipeArtur/nb2pdf)** — Jupyter notebooks and
  print-ready HTML into paginated PDF from the terminal, without LaTeX. A single
  file, and nothing installed into your system Python.
- **[delivery-sql](https://github.com/FelipeArtur/delivery-sql)** — a delivery
  app modelled in 16 tables, written twice: Oracle with `CREATE SEQUENCE` and
  MySQL with `AUTO_INCREMENT`. Watching the same model diverge across dialects
  was half the exercise.

### Coursework

A few assignments from my Computer Engineering degree at SENAI CIMATEC (2020–2025)
live in their own repositories, each with a README explaining what the work does
and how to run it — data structures, operating systems, graph theory, databases,
signal processing and the VR research prototypes. They are tagged
[`senai-cimatec`](https://github.com/search?q=user%3AFelipeArtur+topic%3Asenai-cimatec&type=repositories).

### Now

Specializing in **Data Science & Analytics** at SENAI CIMATEC, through May 2027.
Two published papers: a ground sensor terminal for LoRa-based CubeSat missions
(SpaceLab, UFSC, 2024) and one on virtual reality and eye tracking in Industry
4.0 (IX SAPCT, 2024).
