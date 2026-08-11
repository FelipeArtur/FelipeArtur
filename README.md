<img src="assets/signal.svg" alt="Felipe Artur — Computer Engineer, Salvador, Bahia" width="100%">

Computer Engineer. I work across the whole stack of a product that touches the
physical world: the firmware on the board, the service that collects what it
measures, and the interface where someone finally reads it. The interesting
problems usually sit where two of those meet.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-felipeartur-C62828?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/felipeartur/)
[![Email](https://img.shields.io/badge/Email-felipe.artur.ml@gmail.com-C62828?style=flat-square&logo=gmail&logoColor=white)](mailto:felipe.artur.ml@gmail.com)

---

### Selected work

907 commits across 11 production projects at SENAI CIMATEC, 2023–2026.

- **Medical vacuum system interface** — 245 commits as lead. LVGL on an STM32H753,
  UART with CRC-16, and a desktop Qt simulator that let the screen be built and
  tested without the board.
- **Power datalogger, two years in the field** — 64 of 73 commits. Modbus RTU into
  a cloud time-series database through a disk queue: a reading only leaves disk
  after the write is confirmed, so an outage costs no gap and no duplicate.
- **Nanosatellite ground station dashboard** — 183 commits, ~81%. Separating
  visual config from data mapping cut ~2,900 duplicated lines across six screens.
- **First BI dashboard its department had** — Power BI, DAX by hand. Adopted by
  management, and a system was later built on top of it.

### Stack

| | |
|---|---|
| **Embedded** | C++17, STM32, FreeRTOS, Zephyr, LVGL, MISRA C++, drivers from datasheets, serial protocols with CRC-16 |
| **Web** | TypeScript, React, Django REST, Flask, PostgreSQL, SQLite, JWT |
| **Data** | SQL by hand, relational modelling, pandas, Power BI and DAX, InfluxDB, TensorFlow, PyTorch |
| **Infrastructure** | Linux, Docker, systemd, embedded Linux on Toradex, shell, CI |

### Projects

- **[BrokerShark](https://github.com/FelipeArtur/BrokerShark)** — a local finance
  ledger. Hand-written SQL, forward-only migrations, and the financial invariants
  living as an executable query the audit runs against the real database. Money in
  integer cents.
- **[nb2pdf](https://github.com/FelipeArtur/nb2pdf)** — Jupyter notebooks and
  print-ready HTML into paginated PDF, from the terminal, without LaTeX. One file,
  and nothing installed into your system Python.
- **[delivery-sql](https://github.com/FelipeArtur/delivery-sql)** — a delivery app
  in 16 tables, written twice: Oracle and MySQL. Watching the same model diverge
  across dialects was half the exercise.

### Also

Coursework from my Computer Engineering degree, including the VR research
prototypes, tagged [`senai-cimatec`](https://github.com/search?q=user%3AFelipeArtur+topic%3Asenai-cimatec&type=repositories).
Specializing in Data Science & Analytics through May 2027. Two published papers:
a ground sensor terminal for LoRa CubeSat missions (SpaceLab, UFSC) and virtual
reality with eye tracking in Industry 4.0 (IX SAPCT).
