Web Automation Framework with POM in Python(Selenium)

Tech Stack
* Python, PyTest
* Selenium
* Allure Report
* Gitignore, PyTest Report
* Page Object Model and Page Factory both
* Highlight element while run
* Parallel Run with xdist
* MY SQL data base connect to verify data.

All the dependencies used
1. pip install allure-pytest selenium
2. pip install pytest selenium pytest-html openpyxl
3. pip install selenium-page-factory
4. pip install pyyaml faker openpyxl
5. pip install pytest-xdist
6. pip install mysql-connector-python
7. pip install pytest-reportportal
8. pip install python-dotenv
9. How to run the Framework?
10. pytest -n auto tests/vwoLoginTests/pom/test_*

How to run Testcase parallel ?
pytest -n auto tests/test/vwoLoginTests/test_vwo_login.py
![img.png](img.png)

Dry Run Testcases
![img_1.png](img_1.png)

How to freeze the pip?
use

pip install selenium pytest allure-pytest pytest xdist openpyxl python-dotenv faker selenium-page-factory

pip freeze > requirement.txt

pip install -r requirement.txt
