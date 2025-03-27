# dmm-vs-lookup-etl
 ETL Pipelines Optimization Research Project

## 📊 Evaluating Dynamic Mapping Matrix (DMM) vs Traditional ETL Mapping for Optimized Data Processing

This repository contains the codebase, documentation, and benchmark results for my senior research project, which explores the performance differences between traditional **ETL (Extract, Transform, Load)** mapping methods and a matrix-based approach called the **Dynamic Mapping Matrix (DMM)**.

## 🧠 Project Overview

As modern data systems grow in scale and complexity, optimizing ETL pipelines becomes critical to ensure fast and memory-efficient processing. Traditional ETL methods typically rely on lookup tables and rule-based transformations, which can become computationally expensive as data scales.

This project empirically compares:
	•	Traditional ETL Mapping using lookup tables and direct transformation rules.
	•	DMM-Based Mapping, a compact matrix-based transformation technique introduced in the METL framework.

Both approaches are evaluated using real-world data from the NYC Taxi & Limousine Commission.

## 📂 Contents
	•	traditional_etl/: Implements traditional ETL using Pandas and SQL-like joins
	•	dmm_etl/: Implements DMM-based ETL using Numpy matrix transformations
	•	benchmarking/: Scripts and notebooks to record execution time and memory usage
	•	data/: Dataset references and loading scripts
	•	results/: Performance benchmark results and visualizations
	•	paper/: Final research paper and summary slides (to be added)

## 📈 Performance Metrics

The comparison is based on:
	•	Execution Time (measured using Python’s timeit)
	•	Memory Usage (measured using memory_profiler)

## 🔧 Tools & Technologies
	•	Python
	•	Pandas, Numpy
	•	Jupyter Notebook
	•	PostgreSQL (for optional ETL extensions)
	•	NYC Taxi Trip Data (link)

## 📚 Research Goals
	•	Benchmark DMM vs. traditional lookup-based mapping in realistic scenarios
	•	Quantify trade-offs in performance and memory efficiency
	•	Provide insights for optimizing future ETL workflows

## 🙋 About Me

I’m a senior at Eastern Connecticut State University, double majoring in Computer Science and Business Information Systems, with a minor in Data and Information Engineering. My academic and project background centers on data engineering, and this research supports my goal of contributing to real-world ETL optimization practices.