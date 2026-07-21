# IBM Python for Data Science, AI & Development Portfolio

Welcome to my comprehensive project repository documenting my technical journey through the **IBM Python for Data Science, AI & Development** curriculum. This repository acts as a clean, topic-by-topic showcase of production-ready reference scripts, data engineering foundations, and AI preparation fundamentals.

---

## 📂 Repository Blueprint

### 🎯 Module 1: Python Basics
This directory establishes the programmatic infrastructure required for data engineering pipelines and preprocessing pipelines.

*   **`01_data_types.py`**: Features primitive types (`str`, `int`, `float`, `bool`), memory profiling utilizing `sys.getsizeof()`, explicit type-casting directionality, and underlying integer logic within boolean operations.
*   **`02_expressions_variables.py`**: A mock financial analysis script mapping basic calculations, operational mathematical precedence (PEMDAS rules), standard division vs. integer floor division outputs, and state updates using complex assignment operators.
*   **`03_string_operations.py`**: A dedicated data-sanitization toolkit highlighting positive/negative index slicing, text formatting via escape sequences, and core string cleanup methodologies (`.strip()`, `.replace()`, `.split()`).

---

### 🧱 Module 2: Python Data Structures
This directory focuses on containerized data structures required for handling complex data collections, API responses, and database extractions.

*   **`01_tuples.py`**: Geospatial tracking system showcasing ordered, immutable sequences, heterogeneous data containment, slicing, nesting, and sorting mechanics.
*   **`02_lists.py`**: Dynamic sensor logging tool demonstrating list mutability, addition methods (`.append()`, `.extend()`, `.insert()`), deletion mechanics (`.pop()`, `.remove()`), and memory behavior (Aliasing vs. Deep Copying).
*   **`03_dictionaries.py`**: JSON-like record management parsing key-value mapping, safe data retrieval using `.get()`, key/value/item extraction, and multi-level nested structure traversal.
*   **`04_sets.py`**: Audience analytics engine focusing on automatic data deduplication, membership verification, and mathematical set logic (Unions, Intersections, and Differences).

---

### ⚡ Module 3: Python Programming Fundamentals
This directory covers program flow, modularization, error safety, and object-oriented architecture required for dynamic application design.

*   **`01_conditions_branching.py`**: Automated pipeline validation system applying relational operators, composite logical checks (`and`, `or`, `not`), and nested decisions.
*   **`02_loops.py`**: Iterative data processing engine featuring `for` loops, `range()`, `enumerate()`, flow disruption (`break`, `continue`), and state-driven `while` loops.
*   **`03_functions.py`**: Modular metric calculation toolkit demonstrating scope isolation, positional/keyword parameters, default arguments, and variable inputs (`*args`, `**kwargs`).
*   **`04_exception_handling.py`**: Robust error recovery framework managing `try`-`except`-`else`-`finally` blocks, standard exception handling (`ZeroDivisionError`, `FileNotFoundError`), and custom raises.
*   **`05_objects_classes.py`**: Object-Oriented ETL monitor structuring custom classes, attribute initializers (`__init__`), instance methods, state updates, and object inspection via `dir()`.

---

### 📊 Module 4: Working with Data in Python
This directory houses foundational data processing toolkits, covering raw file I/O operations, structured tabular manipulation with Pandas, and high-performance vector arithmetic with NumPy.

*   **`01_reading_writing_files.py`**: File I/O operations using Python context managers (`with open()`), demonstrating read modes (`'r'`, `'w'`, `'a'`), stream parsing (`read()`, `readline()`, `readlines()`), and automated file cleanup.
*   **`02_pandas_basics.py`**: Structured data analysis toolkit introducing Pandas `Series` and `DataFrames`, structural inspection (`head()`, `info()`, `describe()`), boolean filtering, and explicit indexing via `.loc[]` vs `.iloc[]`.
*   **`03_numpy_basics.py`**: High-performance scientific computing script covering 1D and 2D NumPy arrays (`ndarray`), array inspection attributes (`shape`, `ndim`, `dtype`), mathematical broadcasting, vectorization, and matrix manipulation.

---

### 🌐 Module 5: APIs and Data Collection
This directory highlights external data ingestion architectures, covering HTTP requests via REST APIs, web scraping with BeautifulSoup, and multi-format data persistence.

*   **`01_simple_apis.py`**: Client-side HTTP request engine utilizing the `requests` library to fetch public REST API endpoints, validate HTTP status codes, and load JSON payloads into Pandas DataFrames.
*   **`02_web_scraping.py`**: Web intelligence script demonstrating HTML document fetching, status monitoring, and BeautifulSoup parsing techniques to extract structural elements and text node content.
*   **`03_working_with_files.py`**: End-to-end data pipeline script parsing live API JSON responses and persisting structured records directly into local storage formats (`.json` and `.csv`).

---

## 🛠️ Environment Configuration & Deployment
*   **IDE Context**: GitHub Codespaces / Visual Studio Code (Cloud Architecture)
*   **Language Runtime**: Python 3 interpreter environment
*   **Core Libraries**: `pandas`, `numpy`, `requests`, `beautifulsoup4`