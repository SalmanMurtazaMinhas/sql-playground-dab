# [To use the deloyed site click here 🖱️](http://sql-playground.surge.sh/)

# 🧠 SQL Playground

**SQL Playground** is an interactive, browser-based environment for learning and experimenting with core SQL concepts visually.

Instead of typing queries from scratch, users construct them step-by-step using a structured interface and instantly see:

* The generated SQL
* The query results
* The underlying dataset

Everything runs locally in the browser using SQL.js.

No backend. No setup. Just SQL.

---

## 🎯 Purpose

SQL Playground was built to solve a common problem:

Students often memorize SQL syntax without understanding how clauses reshape data.

This tool shifts the experience from:

> “Writing queries from memory”

to

> “Understanding how each clause transforms a dataset.”

It is designed for:

* Data analytics training
* SQL fundamentals review
* Classroom demonstrations
* Self-paced practice

---

## 🚀 Core Capabilities

### Visual Query Builder

Construct queries using structured controls for:

* SELECT
* WHERE
* GROUP BY
* CASE expressions
* Aggregations (COUNT, SUM, AVG, MIN, MAX)
* ORDER BY
* LIMIT
* ILIKE (implemented via LOWER() for SQLite compatibility)
* IN, IS NULL, IS NOT NULL

JOINs are intentionally excluded to keep the focus on foundational SQL logic.

---

### Live SQL Generation

As the query is built, the exact SQL statement is dynamically generated and formatted.

This allows students to:

* Connect visual structure to real SQL syntax
* Understand how clauses combine
* Learn patterns without copying blindly

---

### Live Result Matrix

Run the generated query and instantly see:

* Output rows
* Column structure
* Row and column counts
* Error feedback if the query fails

The result panel is always visible for fast feedback.

---

### IDE-Style Layout

The interface is structured like a modern development tool.

Left Column

* Build Query
* Define Data

Right Column

* Generated SQL
* Query Results

All panels are resizable for a customizable workspace experience.

---

### Preloaded Dataset

The playground initializes with three tables:

* employees
* orders
* returns

These are automatically seeded on load.

The database can be reset at any time to restore the original state.

---

## 🛠 Tech Stack

* HTML
* CSS
* Vanilla JavaScript
* SQL.js (SQLite compiled to WebAssembly)

The entire database runs in-memory inside the browser.

No server required.

---

## 🖥 Running Locally

Because SQL.js loads a WebAssembly file, the project must be served through a local server.

### VS Code Live Server

1. Install the Live Server extension
2. Right-click `index.html`
3. Select “Open with Live Server”

Then open:

```
http://localhost:8000
```

---

## 🧑‍🏫 Teaching Philosophy

SQL Playground encourages:

* Exploration over memorization
* Visual understanding of execution flow
* Safe experimentation
* Structural thinking

It is built to reinforce how SQL transforms data step-by-step.

---

## 🔮 Possible Future Enhancements

* JOIN module
* Execution order visualizer
* Query history
* Layout persistence
* Challenge mode
* Theme switching

---
# By Salman Murtaza and Zainab Fadhel
