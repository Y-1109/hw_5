## YAĞIZ ÖZKAYA - 2200674057

#  GMT-211 – Homework 5: Project Documentation with Sphinx

In this assignment, I documented my Python project using [Sphinx](https://www.sphinx-doc.org/).  
The documentation is organized under the `docs/` directory and the HTML output has been successfully generated.

---

##  Project Structure

| Folder / File        | Description                                |
|----------------------|--------------------------------------------|
| `docs/`              | Sphinx documentation folder                |
| `docs/conf.py`       | Configuration settings for Sphinx          |
| `docs/index.rst`     | Main table of contents                     |
| `docs/_build/`       | Folder containing generated HTML files     |
| `make html`          | Command to generate HTML output            |

---

##  Tools Used

| Tool / Technology  | Purpose                          |
|--------------------|----------------------------------|
| Python 3           | Programming language             |
| Sphinx             | Documentation generator          |
| Git / GitHub       | Version control and submission   |
| Markdown           | Formatting language for README   |

---

##  AI Assistance

I completed the majority of this assignment on my own.  
However, I used AI tools for brief assistance in the following areas:

- Understanding the role of `sphinx-quickstart` and its generated files  
- Configuring `conf.py`, especially adding `sys.path` for module imports  
- Structuring `.rst` files and using `automodule` and `autodoc` directives  
- Fixing some Git errors related to `remote` and `token-based` authentication  

The AI was used mainly for clarification and troubleshooting.  
The implementation and structure of the documentation were done independently.

---

##  Screenshot (Optional)

> You may add a screenshot of your `docs/_build/html/index.html` here to visualize the result.

---

##  How to Run

To generate the documentation locally, run the following commands in your terminal:

```bash
cd docs
make html
